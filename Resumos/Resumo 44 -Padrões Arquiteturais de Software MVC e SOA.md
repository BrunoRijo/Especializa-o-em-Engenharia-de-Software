# Padrões Arquiteturais de Software MVC e SOA.
>[!Note]
>Resumo 44, Especialização em Eng. de Software por Bruno Rijo

## Arquitetura MVC (Model-View-Controller) 🍎👁🎮 

A arquitetura MVC é um padrão de design que separa uma aplicação em três componentes principais: Modelo, Visão, e Controle. Cada um deles tem uma responsabilidade específica. É utilizado amplamente em frameworks web.

🍎 **Modelo**, gerencia os dados e a lógica da aplicação 

👁 **Visão**, exibe os dados do usuário, é responsável pela interface gráfica.

🎮 **Controle**, atua como intermediário entre o modelo e a visão. Ele recebe as entradas do usuário, processa as solicitações e decide quais partes do modelo ou visão devem ser atualizadas.

Vamos tomar como exemplo um sistema de gerenciamento de tarefas. 
- A camada de modelo, seria a representação de uma tarefa e as suas propriedades, como título, data de vencimento, e o status.
- A camada e visão seria a interface onde o usuário vê a lista de tarefas e os seus detalhes.
- Na camada de controle, quando o usuário marca uma tarefa como concluída, o Controle atualiza o Modelo (status da tarefa) e instrui a Visão a refletir essa mudança.

**Vantagens** 👍 
- Separação de Responsabilidades: Facilita a manutenção e atualização do sistema.
- Reusabilidade: As partes do código podem ser reutilizadas em outras aplicações.

**Desvantagens** 👎 
- Complexidade: Pode ser exagerado para projetos simples, introduzindo uma complexidade desnecessária. 
- Curva de Aprendizado: Desenvolvedores precisam entender claramente a separação entre os componentes.


## Arquitetura Orientada a Serviços (SOA) 👨‍🔧 
Resumidamente, o SOA  é um modelo de arquitetura que organiza a funcionalidade de uma aplicação como um conjunto de serviços distintos e reutilizáveis, que podem ser combinados para construir sistemas complexos. 

Cada serviço fornece um recurso de negócios, e todos eles também podem se comunicar entre si em diferentes plataformas e linguagens. Os desenvolvedores usam a SOA para reutilizar serviços em sistemas diferentes ou combinar vários serviços independentes para realizar tarefas complexas. O SOA é utilizado principalmente em grandes empresas que precisam integrar diferentes sistemas e aplicações de maneira flexível e modular.

Por exemplo,  vários processos de negócios de uma empresa exigem a funcionalidade de autenticação de usuários. Então, para que o código não precise ser reescrito em todos esses processos, o desenvolvedor deve criar um único serviço de autenticação e reutilizar em todas as aplicações.

**Vantagens** 👍
- Manutenção eficiente
- Reusabilidade

**Desvantagens** 👎
- Complexidade
- Possível sobrecarga, que afeta diretamente o desempenho da aplicação;

No próximo resumo, falarei da Arquitetura Pipes-and-filters (PF) e a Arquitetura Peer-to-Peer (P2P)

Você já conhecia esses padrões, ou já trabalhou com algum deles ?

#### #SoftwareEngineer #SoftwareDeveloper #DevDelphi #DevJava #DevKotlin #SoftwareArchitect
