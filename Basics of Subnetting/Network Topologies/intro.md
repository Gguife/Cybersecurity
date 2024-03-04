# Introduction Network Topologies

- Descrevem a disposição de vários dispositivos de rede, suas conexões e os fluxos de dados entre eles.
- Compreender Topologies pode ajudar a identificar vulnerabilidades.
- Compreender Topologies pode melhorar sua postura geral de segurança cibernética.

## Bus Topology
- Todos os dispositivos são conectados a um único meio de comunicação (geralmente um cabo coaxial) denominado "bus".
- Os dados são transmitidos em uma única direção.
- **Vantagens**:
  - Fácil de configurar e estender.
  - Requer menos cabeamento do que outras topologias.
- **Desvantagens**:
  - Se o cabo principal falhar, toda rede falha.
  - O desempenho diminui à medida que mais dispositivos são adicionados.
  - Comprimento e número de dispositivos limitados.

## Star Topology
- Conecta todos os dispositivos a um ponto central ou hub (normalmente switches ou roteadores).
- O ponto central é responsável pela transmissão dos dados entre os dispositivos de rede.
- **Vantagens**:
  - Fácil adicionar ou remover dispositivos sem afetar o resto da rede.
  - Se um dispositivo falhar, isso não afetará toda a rede.
  - Gestão Centralizada.
- **Desvantagens**:
  - Requer mais cabeamento do que a Bus Topology.
  - Se o switch central falhar, toda a rede falhará.

## Ring Topology
- Os dispositivos são conectados em um padrão circular.
- Os dados são transmitidos em uma direção ao redor do anel (círculo), passando por cada dispositivo antes de chegar ao seu destino.
- **Vantagens**:
  - Acesso igual aos recursos para todos os dispositivos.
  - Pode lidar com cargas de alto tráfego.
- **Desvantagens**:
  - Adicionar ou remover dispositivos pode interromper a rede.
  - Se um dispositivo falhar, isso poderá afetar toda a rede.
  - A transmissão de dados pode ser lenta devido à sua estrutura de loop.

## Mesh Topology
- Conecta todos os dispositivos diretamente a todos os outros dispositivos da rede.
- Pode ser completa, cada dispositivo está conectado a todos os outros dispositivos.
- Pode ser parcial, alguns dispositivos estão conectados a todos os outros, enquanto outros mantêm apenas algumas conexões.
- **Vantagens**:
  - Alta tolerância a falhas, tornando-a mais resiliente.
  - Elimina a necessidade de um switch/hub central.
- **Desvantagens**:
  - Requer um grande número de cabos.
  - É caro e difícil de gerenciar.
  - Pode ser um grande desafio configurar e manter.

# 
````
OBS: Topologia Híbrida -> Combina duas ou mais topologias diferentes, como Star e Ring em uma única rede.
````
