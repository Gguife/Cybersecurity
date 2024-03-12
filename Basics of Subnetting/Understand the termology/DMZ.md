# DMZ (Demilitarized Zone)
  - É um parte especifica de uma rede que funciona como buffer.
  - São separados entre a rede interna confiável de um organização e as redes externas nao confiáveis, como a internet.
  - Objetivo principal é isolar o sistema de dados críticos do ambiente externo.
  - Fornece uma camada maior de segurança.

## Objetivo
  - Segurança:
    - DMZ reduz o risco de acessos não autorizados e potenciais danos calsados por ameaças externas.
    - A segurança é feita atravez de fortes controles de acesso, firewalls, sistemas de detectação e prevenção de intrusões(IDS/IPS) para monitoriar e filtrar o tráfego entre o DMZ e as redes internas. 
  - Filtragem de conteúdo:
    - Permite que as organizações coloquem servidores acessiveis ao público sem expor a rede interna.
    - Isso garante que apenas o tráfego autorizado possa passar.
  - Facilidade de gerenciamente:
    - Simplifica os processos de segurança.
    - Fornece um local centralizado para implementação, auditoria e monitoriamento de políticas, regas e configurações de segurança para recursos voltado ao público.

## Componentes
  - Firewalls:
    - Dispositivo usado para controlar e gerenciar o tráfego entre a DMZ, resdes internas e externas.
    - Podem ser configurados para permitir, negar ou restringir o acesso.
  - Proxies:
    - Os servidores porxy atuam como intermediario entre a rede interna e a internt.
    - Eles ajudam a filtrar o tráfego de entrada e saída da web.
  - IDS/IPS:
    - Essas fermanetas monitoram e analisam continuamente o tráfego de rede.
    - Procuram sinais de acesso não autorizado ou atividades maliciosas.
    - Tomam automaticamente ações contra essas ameaças.
  - Servidores voltados ao público:
    - São servidores hospedados na DMZ.
    - Projetados para fornecer conteúdos e recursos a usuários externos.
