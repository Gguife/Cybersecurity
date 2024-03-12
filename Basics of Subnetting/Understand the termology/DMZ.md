# DMZ (Demilitarized Zone)
  - É uma parte específica de uma rede que funciona como buffer.
  - São separados entre a rede interna confiável de uma organização e as redes externas não confiáveis, como a internet.
  - O objetivo principal é isolar o sistema de dados críticos do ambiente externo.
  - Fornece uma camada maior de segurança.

## Objetivo
  - Segurança:
    - DMZ reduz o risco de acessos não autorizados e potenciais danos causados por ameaças externas.
    - A segurança é feita através de fortes controles de acesso, firewalls, sistemas de detecção e prevenção de intrusões (IDS/IPS) para monitorar e filtrar o tráfego entre o DMZ e as redes internas.
  - Filtragem de conteúdo:
    - Permite que as organizações coloquem servidores acessíveis ao público sem expor a rede interna.
    - Isso garante que apenas o tráfego autorizado possa passar.
  - Facilidade de gerenciamento:
    - Simplifica os processos de segurança.
    - Fornece um local centralizado para implementação, auditoria e monitoramento de políticas, regras e configurações de segurança para recursos voltados ao público.

## Componentes
  - Firewalls:
    - Dispositivo usado para controlar e gerenciar o tráfego entre a DMZ, redes internas e externas.
    - Podem ser configurados para permitir, negar ou restringir o acesso.
  - Proxies:
    - Os servidores proxy atuam como intermediário entre a rede interna e a internet.
    - Eles ajudam a filtrar o tráfego de entrada e saída da web.
  - IDS/IPS:
    - Essas ferramentas monitoram e analisam continuamente o tráfego de rede.
    - Procuram sinais de acesso não autorizado ou atividades maliciosas.
    - Tomam automaticamente ações contra essas ameaças.
  - Servidores voltados ao público:
    - São servidores hospedados na DMZ.
    - Projetados para fornecer conteúdo e recursos a usuários externos.
