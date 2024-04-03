# NAT (Network Address Translation)
- É a tradução de endereços de rede.
- Traduz redes de endereços IP de redes privadas em endereços IP públicos para comunicação na internet.
- Ele atua como intermediário entre os dispositivos da rede local (LAN) e a rede externa.

## Como funciona?
- NAT é implementado em um firewall ou dispositivos de redes semelhantes.
- Quando os dispositivos da rede (LAN) se comunicam com as redes externas, o NAT permite que esses dispositivos compartilhem um único endereço IP.
- Tipos de tradução:
  - NAT estático -> Mapeamento um-para-um. Cada endereço privado é mapeado para um endereço público.
  - NAT dinâmico -> Mapeamento um-para-um. Mas o endereço público é escolhido em um pool em vez de ser pré-atribuído.
  - PAT (Tradução de endereços de porta) -> Conhecido como sobrecarga de NAT, PAT mapeia vários endereços privados para um endereço público, usando números de porta de origem exclusivos para diferenciar as conexões.

## Vantagens NAT
- Conservação de endereços IP
- Segurança e privacidade
- Flexibilidade

## Desvantagens NAT
- Problemas de compatibilidade
- Impacto no desempenho
- Conectividade ponta a ponta
