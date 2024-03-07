# VLAN (Virtual Local Area Network)
  - É um agrupamento lógico de dispositivos ou usuários dentro de uma rede.
  - Depesepenham um papel crucial na melhoria de segurança da rede.
  - Permite uma melhor alocação de recursos.
  - Simplifica o gerenciamento de rede.

## Principais recurusos
  - Isolamento -> VLANs isolam o tráfego entre diferentes grupos, assim minizando o risco de acesso não autorizado a dados confidenciais. 
  - Escalabilidade
  - Eficácia em termos de uso
  - Desepenho aprimorado -> Aprimoram o desempenho da rede, diminuindo o tráfego desnecessário.

## Tipos de VLANs
  - VLANs baseadas em portas
    - Aqui os dispositivos são separados com base na sua conexão física com o switch.
    - Cada porta é atribuida a uma VLAN específica.
  - VLANs baseadas em protocolos
    - Os dispositivos são agrupados com base no tipo de protocolo de rede que usam.
    - Por exemplo, todos os dispositivos IP podem ser atribuídos ao uma VLAN, enquanto, dispositivos IPX podem ser atribuídos a outra.
  - VLANs baseadas em MAC
    - São atribuidos com base no seu endereço MAC.
    - Oferecem melhor sergurança e flexibilidade, mas requer mais esforço administrativo.

## Criando e gerenciando VLANs
  - São criadas e gerenciadas por meio de switches de rede que suportando configuração VLAN.
  - Switches usam um ID de VLAN para indentificar excluisivamente cada VLAN.
  - O VLAN Trunking Protocol (VTP) e o padrão IEEE 802.1Q são normalmente usados ​​para gerenciar VLANs.

## Segurança
  - O salto de VLAN e o acesso não autorizado ainda podem ocorrer sem medidas adequadas.
  - VLANs privadas e listas de controle de acesso (ACLs), não forem implementadas para proteger a rede. 