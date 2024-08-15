# Diagrama de Classes 📚
>[!NOTE]
>Resumo 16, Especialização em Engenharia de Software por Bruno Rijo

No ultimo post, fiz uma breve introdução do que é a UML. 
Bora agora falar um pouco sobre o primeiro deles:

## Diagrama de Classes

É considerado o principal diagrama, dentre os 14 que compõem a UML. Um ponto interessante é que ele representa o sistema do ponto de vista dele mesmo, ou seja, de dentro para fora. É uma representação estática do sistema que será desenvolvido.

Sendo a UML totalmente baseada na orientação a objetos, o diagrama de classes possui uma representação visual para cada elemento da OO. 
Assim, uma classe é constituída de atributos e métodos, sendo completa quando apresentar ambos os conceitos, ou parcial quando apresentar somente um. 

Um atributo é um termo referente a cada característica de uma classe, e método se refere a cada ação/comportamento que essa classe pode realizar 

Outros conceitos importantes também são trabalhados no diagrama de classes, como: Associação, agregação, composição e multiplicidade.

🤓 Vamos aos conceitos:

A herança pressupõe que uma classe pode herdar características de uma ou mais classes ditas como “ancestrais”, além de ter suas próprias características por definição. A grande vantagem de se utilizar a herança é a organização e a eliminação de redundâncias no código.

Através do uso da herança, onde pode-se criar vários níveis de abstrações, praticamente uma árvore genealógica de classes, podemos estabelecer outros dois conceitos derivados: 

- Generalização
Esse conceito sugere a visualização dessa árvore de baixo para cima, onde cada nível acima é mais genérico/abrangente.

- Especialização
 O contrário da generalização, indica a visualização de cima para baixo, onde cada nível se apresenta de modo mais específico.


Sendo assim, a ideia de herança trás a tona os termos SUPERCLASSE e SUBCLASSE. Onde a superclasse é a classe “mais alta”, ou seja, a primeira criada, e subclasse sendo qualquer classe que derive de outra classe.

😁 Outros conceitos:

- Associação é a ligação entre duas ou mais classes, relacionando elas entre si. 
- Multiplicidade, ou cardinalidade, se refere ao relacionamento entre os objetos gerados a partir das classes associadas, sendo representada por valor com 0 e 1, ou por intervalos como: 1 para N, 0 para N, N para N, ou quaisquer valores mais específicos.
- Agregação é um tipo de associação que indica que as algumas informações de uma classe (chamada todo) precisam ser complementadas por outras contidas em uma ou mais classes menores (chamada parte).
- Composição é semelhante ao conceito de agregação, porém aqui uma classe “todo” é responsável por criar e destruir suas “partes”. Assim uma “parte” não pode ser associada a mais de um “todo”.

Em anexo deixei uma imagem com a representação visual de todos esses conceitos! 

![image](https://github.com/user-attachments/assets/00312332-a6c5-46aa-8a90-24617a27978a)


#### Referência
- PRESSMAN, R. S. Engenharia de software: uma abordagem profissional. 8. ed. Porto Alegre: AMGH, 2016.

#### #SoftwareEngineer #Java #Kotlin #Delphi
