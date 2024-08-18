# Revisando Conceitos de Orientação a Objetos 📦 
>[!Note]
Resumo 24, Especialização em Eng. de Software por Bruno Rijo

A POO é uma maneira de identificar os elementos do mundo real, abstraindo os grupos de objetos e suas respectivas relações para um modelo computacional. Abordarei a seguir, os conceitos que fundamentam esse paradigma:

- **Objeto**: É qualquer coisa concreta ou abstrata do mundo real, com características e comportamentos próprio, sendo possível ser identificado. Exemplo: Carro, Produto, Cliente, Contrato, Ingresso .. etc.
- **Abstração**: Pode ser definida como um processo mental pelo qual nós, seres humanos, nos concentramos em aspectos mais importantes de alguma coisa, enquanto ignoramos os aspectos menos importantes. A abstração sempre depende do contexto sobre o qual algo é analisado, o que é importante em um contexto pode não ser em outro.
- **Classe**: Cada ocorrência de um objeto representa uma instância de uma classe, ou seja, como foi definido por Booch, Rumbaugh e Jacobson(2006), uma classe é uma “descrição de um conjunto de objetos que compartilham os mesmos atributos, operações, relacionamentos e semântica.
- **Atributos**: Representa uma característica de um objeto de uma classe, assumindo valores específicos para cada objeto.
- **Operação**: Também conhecida como Função ou Método, descreve uma ação que o próprio objeto executa, ou que pode ser executada por ele a partir de um evento, sendo comum a todos os objetos da mesma classe.
- **Eventos**: São acontecimentos que provocam mudança de estado dos objetos.
- **Estado**: É a forma como um objeto se apresenta em um dado periodo de tempo.
- **Encapsulamento**: Na definição de Rumbaugh, “também é chamado de ocultamento de informações, consiste na separação dos aspectos externos de um objeto, acessíveis por outros objetos, dos detalhes internos da implementação, que ficam ocultos aos demais objetos.”
- **Generalização**: Também conhecida como Herança, consiste na propriedade pela qual uma classe pode herdar atributos e operações de uma classe que generaliza características comuns a um grupo de objetos. Aqui entra novamente o conceito de superclasse e subclasse que eu abordei nos resumos anteriores.
- **Polimorfismo**: Esse conceito está diretamente ligado à herança, porem mais especificamente no comportamento das operações. Consiste na redeclaração de uma operação em subclasses, e uma implementação diferente da que está na classe pai.

Por enquanto é isso, nos próximos resumos trarei alguns diagramas utilizados na etapa de modelagem que ainda não abordei como Diagrama de Atividades, de Máquina de estados, de pacotes, etc ..

#### #EngenhariaDeSoftware #SoftwareEngineer #Java #Kotlin #Delphi #SoftwareDeveloper

**Referências**:
- Catarino, Iolanda Cláudia Sanches. Modelagem do sistema com a análise orientada a objetos. Londrina: Editora e Dist. Ed. S.A., 2020.
- BOOCH, Grady; RUMBAUGH, James; JACOBSON, Ivar. UML: guia do usuário. 2. ed. Rio de Janeiro: Campus, 2006.
