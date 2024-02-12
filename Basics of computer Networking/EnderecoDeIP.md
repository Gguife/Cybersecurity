# Endereço IP
É um identificador exclusivo atribuído a cada dispositivo em uma rede.<br>
### Existem dois tipos: 
- IPV4
- IPV6

## IPV4
- Usa um sistema de endereçamento de 32 bits.
- Sua estrutura é em octeto, ou seja, o número binário de endereço IP tem 8 bits (Lembrando que os números do endereço de IP vão de 0 a 255, justamente para serem octagonal. Ex: 10.1.0.255)
- O endereço e a máscara de rede determinam a qual rede o dispositivo pertence.

## IPV6
- Usa um sistema de endereçamento de 128 bits.
- Fornece um número significamente maior de endereços que o IPV4. 

## Métodos de comunicação (IPV4, IPV6)
- Unicast
  - Comunicação feita de 1 para 1.
- Anycast
  - Comunicação feita de 1 para muitos. (Tem que estar na mesma região).
- Broadcast
  - Quando um dispositivo se comunica com alguns receptores.
- Multicast
  - Método de transferência simultânea para diversos receptores.


### OBS: Uma pequena analogia para o entendimento sobre endereço de rede e endereço Host.<br>
- Endereço de Rede = CEP da Rua.
- Endereço Host = número da casa.
