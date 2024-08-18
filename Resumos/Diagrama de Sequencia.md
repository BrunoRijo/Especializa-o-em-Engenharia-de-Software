# Diagrama de Sequência ⏩ 
>[!Note]
>Resumo 18, Especialização em Eng. de Software por Bruno Rijo

Seguindo os estudos dos diagramas UML, vamos falar sobre o **Diagrama de Sequência**, que pode ser definido como uma representação do sistema em execução, ele equivale à uma visualização gráfica do passo a passo de ações executadas no sistema e também os possíveis comportamentos decorrentes de cada uma dessas ações.

Deve ser desenvolvido para cada caso de uso, e para cada situação QUE ESTEJAM VINCULADOS A UM ATOR! Lembrando que não dá pra desenvolver o diagrama de sequência sem que os casos de uso e de classes estejam prontos, pois ele utiliza os elementos empregados nesses dois.

Os componentes de um diagrama de sequencia são:
- **Linha de vida**: Representa o tempo em que um objeto existe durante o processo
- **Atores**: Assim como em casos de uso, são os atores envolvidos.
- **Objetos**: Representam a instancia de classes envolvidas no processo.
- **Trocas de Mensagens**: Representam a comunicação entre objetos e/ou atores.
- **Mensagens de retorno**: O retorno dado a um objeto que o chamou
- **Mensagens de Auto chamada**: Mensagens que partem a linha de vida de um objeto e atingem a linha de vida do próprio objeto.

👍 Vantagens
- Facilita o entendimento dos devs que trabalham no projeto
- Pode servir como documentação
- Ganhos de otimização e trabalho em equipe.

👎 Desvantagens
- Caso o contexto onde for aplicado for grande, demanda muito tempo, e mais pessoas para gerenciar e manter o diagrama.

### Exemplo

![image](https://github.com/user-attachments/assets/a328a738-1cc7-4ee1-880f-f6c8519ef644)


Um software para executar diagramas UML são o **ASTAH, Microsoft Visio** e até mesmo o **NetBeans IDE** e o **Eclipse IDE**.

**REFERÊNCIAS**: 

Universidade Luterana do Brasil. Professor Vinicius Silveira Magnus.
FABRIS, P. P. G.; PERINI, L. C. Processos de software. Londrina: Editora e Distribuidora Educacional S.A., 2014.
