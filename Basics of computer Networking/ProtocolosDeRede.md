# Protocolos de Rede
- ### O que é um protocolo de rede?
    Protocolos são um conjunto de regras que gerenciam a comunicação entre dispositivos dentro de uma rede.

### PRINCIPAIS PROTOCOLOS DE REDE:
- TCP/IP
- UDP
- HTTP
- HTTPS
- SSH
- FTP
- SFTP
- DHCP
- SMTP

## TCP/IP TCP(Transmission Control Protocol) IP(Internet Protocol)
Entre os protocolos, TCP/IP é o mais utilizado, visto que todos os outros têm como base o TCP/IP. <br>
É responsável pelo envio e o recebimento confiável de dados pela internet e estabelece a conexão entre dispositivos.
- TCP: Garante essa conexão e envio confiável.
- IP: Facilita o envio de pacotes de dados, atribuindo endereços de IP para identificar os dispositivos.

## UDP (User Datagram Protocol)
- É um protocolo leve e rápido mas menos confiável em relação ao protocolo TCP, frequentemente usado em aplicativos de Stream, jogos, videochamadas.

## HTTP (HyperText Transfer Protocol)
- Aqui temos o principal elemento para acesso a sites da internet, estabelecendo a conexão entre o navegador e o servidor.<br> 
- É como se o navegador pedisse permissão de acesso à página que se deseja acessar e o servidor responde liberando a permissão e os arquivos da página. 

## HTTPS (HyperText Transfer Secure)
- O HTTPS funciona da mesma forma que o HTTP, só que com muito mais segurança.<br>
- Esse reforço de segurança acontece por meio de certificação digital, capaz de criptografar dados.<br>
- Comumente utilizado em site de e-commerce e sites que com sistemas de pagamento.

## SSH (Secure Shell)
- Seria como um Bloqueio de Segurança, visa aumentar a segurança na troca de arquivos entre sistemas computacionais envolvidos.
- SSH opera por meio de login e senha, que permitem verificar e autenticar a legitimidade do servidor que o cliente deseja acessar.

## FTP (File Transfer Protocol)
- Conhecido como protocolo de transferência de arquivos. <br>
- É a uma forma simples, rápida e versátil de transferir arquivos entre dois computadores pela internet.
- O FTP opera da seguinte forma: 
  - O computador que solicita a conexão (cliente) 
  - O computador que aceita o pedido e fornece os dados solicitados (servidor) 

## SFTP (Simple File Transfer Protocol)
- SFTP opera da mesma forma que o FTP, mas com uma camada maior de segurança.
- A comunicação entre os dois computadores é autenticada.
- O usuário pode definir a quantidade de arquivos a serem transmitidos simultaneamente, além de estabelecer senha para fortalecer a segurança.
- Tudo isso é possível ao SSH.

## DHCP (Dynamic Host Configuration Protocol)
- Conhecido como configuração dinâmica de endereço de rede (DYNAMIC HOST CONFIGURATION PROTOCOL).
- Permite que todos os dispositivos e computadores conectados à internet obtenham endereços de IP de forma automática.

## SMTP (Simple Mail Transfer Protocol)
- É um protocolo de transferência de emails.
- Após a definição dos destinatários, a mensagem é autenticada e enviada ao protocolo SMTP que se encarrega de entregá-la.
