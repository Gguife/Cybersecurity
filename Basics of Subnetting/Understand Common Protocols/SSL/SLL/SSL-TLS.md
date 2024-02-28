# SSL/TLS
- SSL (Secure Sockets Layer)
- TLS (Transport Layer Security)
- São protocolos criptografados, projetados para fornecer uma comunicação segura em uma rede de computadores.
- Auxiliam na proteção de informações confidenciais transmitidas online, como:
  - Credenciais de Login.
  - Informações financeiras.
  - Dados privados de usuários.

# SSL
- É o antecessor do TLS.
- Usa uma combinação de métodos de criptografia simétrica e assimétrica, bem como certificados digitais, para estabelecer e manter uma comunicação segura.

# TLS
- É uma versão aprimorada e mais segura do SSL.
- Fornece uma estrutura de segurança mais robusta e flexível.
- SSL foi substituído pelo TLS, onde o TLS se tornou o padrão de práticas recomendadas para comunicação segura.

## Componentes Chave
- Criptografia: SSL e TLS usam algoritmos poderosos para proteger os dados, garantindo que sejam ilegíveis por qualquer pessoa sem as chaves de descriptografia adequadas.
- Autenticação: Os certificados digitais SSL/TLS verificam as identidades do cliente e do servidor, garantindo confiança e autenticidade.
- Integridade: Esses protocolos de segurança utilizam códigos de autenticação para garantir que os dados enviados entre cliente e servidor não foram adulterados durante a transmissão.

## Como funciona SSL/TLS
  - Eles operam criptografando os dados transmitidos entre um cliente e servidor.
  - Garantem que os dados não possam ser facilmente interceptados ou alterados.
  
## As principais etapas para configurar uma conexão SSL/TLS
  ### Handshake:
  - Cliente e servidor se envolvem em um processo chamado ``Handshake`` para estabelecer uma conexão segura.
  - Nesse processo, cliente e servidor concordam em qual versão utilizar o SSL/TLS.
  - Escolhem os conjuntos de criptografia.
  - Escolhem os algoritmos criptográficos que usarão para proteger a comunicação.

  ### Troca de chaves:
  - Aqui é onde realizam a troca de chaves.
  - Aqui é um processo pelo qual eles geram e compartilham chaves criptografadas com segurança.
  - Essas chaves são usadas para criptografar e descriptografar os dados transmitidos entre eles.

  ### Verificação de certificado: 
  - Aqui o servidor fornecerá um certificado digital.
  - Nesse certificado contém sua chave pública e informações sobre o servidor.
  - Cliente verifica a validade, sabendo se foi emitido por uma Autoridade de Certificação (CA).
  
  ### Comunicação Segura:
  - Assim que todas as etapas anteriores forem concluídas, o cliente e servidor podem começar a transmitir dados com segurança usando as chaves de criptografia que compartilharam.
