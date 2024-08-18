# Diagrama de Casos de Uso
>[!Note]
>Resumo 17, Especialização em Eng. de Software por Bruno Rijo

O diagrama de casos de uso é o diagrama mais geral da UML. Ele representa o ponto de vista do usuário, ou seja, de fora para dentro.

Um caso de uso representa uma ação a ser realizada no sistema de software, ou seja, ele representa uma funcionalidade do sistema.

Os elementos que compõem esse diagrama são:
- 🙎‍♂️ Ator é um elemento (pode ser uma pessoa, equipamento, outro sistema) que irá interagir diretamente com o software a ser desenvolvido.
- 💭 Caso de uso é a uma ação realizada pelo sistema. Deve ser escrita como um verbo no infinitivo.
- ↔ Associação é a ligação entre os atores e casos de uso.

Apesar de ser o diagrama mais geral, ele possui recursos específicos e mais refinados.

A **herança** é representada utilizando o mesmo símbolo tanto para casos de uso quanto para atores, em seu uso, um ator pode herdar as mesmas características e ações de outro.

Há duas formas de identificar o relacionamento entre dois ou mais casos de uso existentes em um diagrama. São elas: **include** e **extends**:

➡ include: Pressupõe que uma ação sempre será realizada automaticamente pelo sistema quando outra ação for realizada. 
Exemplo: Suponha que um caso “A” inclui outro caso “B”, Isso significa que ao executar o caso A, implica consequentemente em executar o caso B. Ou seja, sempre que o caso A for executado, o caso B também será.

➡ extend: Segue o mesmo conceito do include, porém não acontece de maneira automática, é necessário que alguma condição seja atendida para que a ação B seja executada, em detrimento da função A. 
Exemplo: O bloqueio de acesso de um usuário ao sistema quando ele digitar a senha errada por três vezes consecutivas.

Referências

PRESSMAN, R. S. Engenharia de software: uma abordagem profissional. 8. ed. Porto Alegre: AMGH, 2016.

#### #EngenhariaDeSoftware #SoftwareEngineer#Java #Kotlin #Delphi #DesenvolvedorDeSoftware #SoftwareDeveloper
