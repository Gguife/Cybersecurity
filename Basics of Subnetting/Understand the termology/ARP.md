# ARP - Protocolo de resoleção de endereços
  - É um protocolo usado pelo IP(Internet Protocol).
  - Utilizado para mapear o endereço IP para um endereço físico, tambem conhecido como endereço MAC.
  - É essencial para rotear dados entre dispositivos e uma rede local (LAN), pois permite a traduçao de endereços IP para hardware especifico na rede.

## Como funciona
  - Quando um disposito deseja se conectar com outro dispostivo na mesma rede local, ele precisa determinar o endereço MAC correspodente ao endereço IP de destino.
    - O ARP ajuda neste processo, transmitindo uma solicitação ARP contendo o endereço IP do destino.
    - Todos os dispositivos recebem esta solicitação e comparam o endereço de IP com os seus proprios IPs.
    - Se for encontrado o dispositivo que contem este endereço, o dispositvo envia uma respota ARP que contém o seu endereço MAC.

## Preocupações com segurança
  - ARP apresenta certos riscos de segurança, como por exemplo:
    - O evenenamento por ARP: Ocorre quando o invasor envia mensagens ARP falsas com objetivo de associar seu endereço MAC com o endereço IP de um dispositivo alvo.
      - Isso levam a ataques Man-in-the-Middle (MITM): Onde o invasor pode inteceptar, modifcar, ou bloquear o tráfego destinado ao dispositivo.