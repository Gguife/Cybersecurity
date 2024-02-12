# Camadas de Rede (Modelo OSI)

<div align="center">
  <img src="../public/camadasDeRede.png" alt="Gráfico camadas de rede">
</div>

## Modelo OSI (Open Systems Interconnection)
- O modelo OSI é uma estrutura usada para compreender e descrever como diferentes protocolos de rede se comunicam.
- No modelo OSI essas funções são divididas em 7 camadas:
  - Camada Física
  - Camada de Enlace
  - Camada de Rede
  - Camada de Transporte
  - Camada de Sessão
  - Camada de Apresentação
  - Camada de Aplicação

## Camada Física
- Aqui é onde se localiza a parte dos cabiamentos e Hardwares.
- Lida com a conexão física entre os dispositivos.

## Camada de Enlace
- Aqui se refere às tecnologias que são usadas para conectar duas máquinas em uma rede onde a camada Física já existe.
- O controle de fluxo e o controle de erros de dados geralmente são os principais focos desta camada.
- Essa camada é composta por duas partes:
  - Controle de enlace lógico (LLC): Que identifica e checa erros;
  - Media Access Control (MAC): Que usa endereços MAC para conectar e definir permissões no dispositivo;
### MAC
- É um identificador exclusivo.
- Funciona com um número de série de 48 bits.
- Pode identificar um dispositivo de rede Ethernet ou Wifi.
- Switch utiliza para endereçar e encaminhar as informações.

## Camada de Rede
- Nessa camada tem como importante função cuidar dos pacotes de roteamento, selecionando o caminho mais curto para isso.
- Na internet o IPV4 e IPV6 são usados como principais protocolos da camada de rede.

## Camada de Transporte 
- O principal foco desta camada é garantir que os pacotes de dados enviados cheguem na ordem correta, sem perdas, erros ou que possam ser recuperados sem complicações.
- Nessa camada os principais protocolos usados são o TCP e UDP.

## Camada de Sessão
- Essa camada é responsável por abrir sessões e garantir que tudo esteja funcional para que os dados possam ser transferidos.
- Uma sessão gerencia o início e o término de uma conexão individual.
- NFS(Network File System) e SMB(Server Message Block) são os protocolos comumente usados.

## Camada de Apresentação
- É a camada que faz a preparação dos dados para a camada de aplicação.
- A camada se preocupa principalmente com a sintaxe dos dados para a aplicação enviar e consumir.
- Exemplo de linguagens comuns nessa camada são o HTML, JSON.

## Camada de Aplicação
- Aqui os navegadores podem se comunicar usando o HTTPS, e clientes de e-mail e HTTP podem se comunicar usando POP3(Post Office Protocol version 3) e o SMTP.
- Aqui é onde permitem que um software receba informações significativas para o usuário.
