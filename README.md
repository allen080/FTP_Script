# Programa para transferência de arquivos entre computadores via FTP
Autor: Luan Fellipe (allen08)

Necessário:
- python (>= 3.2)
- lib pyftpdlib (instalar: pip install pyftpdlib)
- Opcional (para compartilhamento entre diferentes redes): ngrok.exe + chave de autenticação (https://ngrok.com/download)

OBS: ambos os códigos foram feitos para o ambiente Windows, nao testei sua funcionalidade em linux.

Client:
Cliente ftp feito em python para fazer downloads de arquivos em um servidor ftp. 
O script busca facilitar as pessoas na hora de se conectar a um ftp.

Server:
Cria um server ftp na maquina local do usuario. O server pode ser criado em uma determinada pasta, para assim ser feito o download dos arquivos pelo cliente
suporta tbm o ngrok.

*obs: Para envio entre diferentes redes, o ngrok (https://ngrok.com/download) ja precisa estar instalado na maquina, no diretorio C:\Windows\System32 (Windows) ou na pasta do projeto, e com sua chave de autenticação.




