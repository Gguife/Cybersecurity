# Camadas de Rede (Modelo OSI)

<div align="center">
  <img src="../public/camadasDeRede.png" alt="Grafico camadas de rede">
</div>

## Modelo OSI (Open Systems Interconnection)
  - O modelo OSI é uma estrutura usada para compreender e descrever como diferentes protocolos de rede se comunicam.
  - No modelo OSI essas funções são dividias em 7 camadas.
    - Camada Física
    - Camada de enlace
    - Camada de Rede
    - Camada de Transporte
    - Camada de Sessão
    - Camada de Apresentação
    - Camada de Aplicação

## Camada Física
  - Aqui é onde se localiza a parte dos cabiamentos e Hadwares.
  - Lida com a conexão física entre os dispositivos.

## Camada de Enlace
  - Aqui se refere às tecnologias que são usadadas conectar duas maquinas em uma rede onde a camada Física já existe.
  - O controle de fluxo e o controle de erros de dados geralmente são os principais focos desta camada.
  - Essa camada é composta por duas partes:
    -  Controle de enlace logico (LLC): Que indentifica e checa erros;
    -  Media Access Control (MAC): Que usa endereços MAC para conectar e definir permissões no dispositivo;
### MAC
  -  É um indentificador exclusivo.
  -  Funciona com um número de série de 48 bist.
  -  Pode indentificar um dispositivo de rede Ethernet ou Wifi.
  -  Switch utiliza para endereçar e ecaminhar as informações.

## Camada de Rede
  - Nessa camada tem como importante função cuidar dos pacotes de roteamento, selecionando o caminho mais curto para isso.
  - Na internet o IPV4 e IPV6 são usados como principais protocolos da camada de rede.

## Camada de Transporte 
  - O principal foco desta camada é garantir que os pacotes de dados enviados cheguem na ordem correta, sem perdas, erros ou que possam ser recuperados sem complicações.
  - Nessa camada os principais protocolos usados são o TCP e UDP.

## Camada de Sessão
  - Essa camada é responsável por abrir sessões e garantir que tudo esteja funcional para que os dados possam ser transferidos.
  - Uma sessão gerencia o inicio e o término de uma conexão individual.
  - NFS(Network file system) e SMB(Server Mesage Book) são os protocolos comumente usados.

## Camada de Apresentação
  - É a camada que faz a preparação dos dados para a camada de aplicação.
  - A camada se preocupa principalmente com a sintaxe dos dados para a aplicação enviarem e consumirem.
  - Exemplo de linguagens comums nessa camada são o HTML, JSON.

## Camada de Aplicação
  - Aqui os navegadores podem se comunicar usando o HTTPS, e clientes de e-mail e HTTP podem se comunicar usando POP3(Post Office Protocol version 3) e o SMTP.
  - Aqui é onde permitem que um software receba informações significativas para o usuário.