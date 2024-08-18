# Diagrama de Atividades 🏃‍♀️ 📊 
>[!Note]
>Resumo 25, Especialização em Eng. de Software por Bruno Rijo

Como já era esperado da cadeira de Modelagem, voltarei abordar os diagramas UML.

Porém, como já falei dos 3 principais que foram: Diagrama de Classes (Resumo 16), Diagrama de Casos de Uso (Resumo 17) e Diagrama de Sequência (Resumo 18), abordarei daqui pra frente os demais. Começando pelo diagrama de Atividades. 

Bora lá!?

Considerando que os casos de uso já tenham sido especificados, esse diagrama demonstra o fluxo de atividades que representam a execução dos procedimentos, casos de uso, processos de negócio, subsistemas e até mesmo  sistema completo.

(Bezerra 2014, p.307) define esse diagrama como uma “extensão dos fluxogramas, além de possuir toda a semântica existente em um fluxograma, o diagrama de atividade possui a notação para representar ações concorrentes juntamente com a sua sincronização.”

Os elementos básicos da notação de um diagrama de atividades são:

- **Atividade**: Representada por um retângulo maior com bordas arredondadas, refere-se a sequência de tarefas em um fluxo de trabalho que resulta em um comportamento de um processo. Usa-se verbo no infinitivo.
- **Nó de ação**: Representado por um retângulo menor com bordas arredondadas, com um nome que descreve uma ação Indica a execução de um passo imediato de uma atividade. 
- **Nó inicial**: Representado por um círculo preenchido, indica a primeira atividade do fluxo Obrigatoriamente um D.A. só deve ter um único nó inicial.
- **Nó final**: Representado por um círculo preenchido dentro de um vazio, indica o fim do fluxo. Um D.A pode ter um ou mais nós finais.
- **Nó de decisão**: Representado por um losango com dois ou mais fluxos de escolha, é acompanhado por condições de guarda que indicam a condição que pode escolhida.
- **Nó de objeto**: Representado por um retângulo com o nome do objeto. Corresponde a uma instância de uma classe.
- **Fluxo de controle**: Representado por uma reta com uma seta na ponta, pode ou não conter uma descrição. Indica a ligação de dois nós.
- **Fluxo de Objeto**: Representado por uma reta com uma seta na ponta, realizado entre um nó de ação e um nó de objeto, usado para modificar o estado de um objeto.
- **Nó de bifurcação (Fork)**: Representado por uma barra espessa na horizontal ou vertical, usado quando há dois ou mais fluxos de entrada e somente um de saida.
- **Nó de União (Join)**: Também representado por uma barra espessa na horizontal ou vertical, entretanto, usado em casos de uma entrada e dois ou mais fluxos de saída.
- **Partições (Swinlanes)**: Representado por retângulos longos em forma de compartimentos, permitem representar o fluxo de um processo que interage por diferentes atores participantes.

## Exemplo
![image](https://github.com/user-attachments/assets/b933566d-6cc2-4494-a7d4-1a23a14cb52c)


No próximo resumo, trago o diagrama de máquina de estados!! até lá :)

#### #EngenhariaDeSoftware #SoftwareEngineer #Java #Kotlin #Delphi #DesenvolvedorDeSoftware #SoftwareDeveloper
