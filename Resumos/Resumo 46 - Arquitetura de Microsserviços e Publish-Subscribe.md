# Arquitetura de Microsserviços (Microservices) e Publish-Subscribe (Pub/Sub)
>[!Note]
>Resumo 46, Especialização em Eng. de Software por Bruno Rijo

## Arquitetura de Microsserviços (Microservices) 👶 🔧 
Acredito que praticamente todo mundo que é do TI já ouviu falar em microsserviços hahaha

Trata-se de um padrão onde a aplicação é estruturada em um conjunto de serviços pequenos, independentes e autônomos. Cada microsserviço é responsável por uma funcionalidade específica e pode ser desenvolvido, implantado e escalado de maneira independente. É bastante utilizada em sistemas grandes e complexos que precisam ser escaláveis e flexíveis como aplicações empresariais, e-commerce e etc.

A comunicação entre os microsserviços, na grande maioria das vezes, acontece por meio de API’s, e cada microsserviço pode ser desenvolvido em uma linguagem diferente, utilizar diferentes bancos de dados e serem implantados de maneira independente uns dos outros.

**Exemplo**: Um microsserviço de pagamento que utiliza Node.js e um banco de dados NoSQL  pode se comunicar com um microsserviço de inventário feito em Java com MySQL através de uma api, para verificar a disponibilidade de um item antes de confirmar uma compra.

**Vantagens** 👍 👍 
- Flexibilidade de desenvolvimento: Cada equipe pode trabalhar em um microsserviço diferente utilizando a linguagem ou framework que se adeque melhor.
- Resiliência: Falhas em um microsserviço não afetam diretamente o funcionamento dos demais.

**Desvantagem** 👎 👎 
Complexidade operacional: Pode ser difícil gerenciar, monitorar e manter vários serviços independentes..


## Arquitetura Publish-Subscribe (Pub/Sub) 👩❗ 

Publish, significa “Publicar” e Subscribe significa “Inscrever-se”, a gente lida com esses dois termos diariamente, e assim como o nome sugere, é um modelo arquitetural utilizado em diversas redes sociais que torna possível a comunicação entre os produtores de conteúdo e os consumidores. Ao disponibilizar novos conteúdos os consumidores, que estão de alguma maneira associados ao produtor de conteúdo, recebem notificações, podendo assim consumir tal conteúdo.

**Vantagens** 👍 👍 
- Escalabilidade: Facilita a distribuição de mensagens para múltiplos assinantes sem sobrecarregar o publicador.
- Flexibilidade: Assinantes podem se associar a vários publicadores e a lógica de processamento pode ser distribuída de modo eficiente.

**Desvantagens** 👎 👎 
- Complexidade:  A implementação de um sistema Pub/Sub pode ser complexa em termos de configuração e manutenção.
- Garantia de Entrega: Pode ser um desafio entregar corretamente mensagens a um grande volume de assinantes, especialmente em sistemas distribuídos.

**Referência**:
- Arquitetura de software / Anderson da Silva Marcolino. – São Paulo: Platos Soluções Educacionais S.A., 2022.
