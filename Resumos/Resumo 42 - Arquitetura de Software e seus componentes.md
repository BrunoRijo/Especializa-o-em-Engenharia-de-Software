# Arquitetura de Software e seus componentes 🏘 
>[!Note]
>Resumo 42, Especialização em Eng. de Software por Bruno Rijo

Assim como na construção de uma casa ou prédio,  é necessário pensar na estrutura arquitetural dos projetos de software.

A arquitetura de Software é o resultado de diferentes interações entre diversos artefatos analisados, projetados e estabelecidos nas etapas trabalhadas na Engenharia de Software, em outras palavras, a arquitetura de Software é uma subárea da Engenharia de Software.

Nas etapas da Engenharia de Software, após as fases de análise de requisitos e projeto, onde são reunidos os artefatos produzidos até o momento como: **Especificação de requisitos, Projeto de Interface, Projeto de Componentes e Projeto de Banco de Dados**, a arquitetura é definida interligando o projeto de interface e de banco de dados, e contemplando também os componentes. É nessa fase onde tudo toma o seu devido lugar, e são definidas as tecnologias e padrões que serão adotados para se criar o software final. Sommerville (2018, p. 42) define o projeto de arquitetura como um projeto “no qual você pode identificar a estrutura geral do sistema, os componentes principais (algumas vezes, chamados subsistemas ou módulos), seus relacionamentos e como eles são distribuídos”.

O sucesso da arquitetura de um sistema está ligado diretamente ao design e a implementação. Design é uma forma de analisar e compreender as interações entre as partes do sistema, considerando impactos que possíveis mudanças podem causar em outro componente que o acessa direta ou indiretamente (SILVEIRA et al., 2011; SOMMERVILLE, 2018).

Já a implementação, não se remete apenas a escrita de código, mas também às escolhas de ferramentas, versões no ambiente de desenvolvimento, homologação e produção, linguagem de programação adotada, legibilidade do código, entre outras. Tais itens modelam a implementação de um sistema, assim como sua qualidade (SILVEIRA et al., 2011; PRESSMAN, 2021). É importante destacar que diversos modelos são necessários para compor e representar uma arquitetura.

Arquitetura é um outro modo de interpretar a implementação, analisando e compreendendo como uma mudança em um ponto do sistema, afeta a solução por inteiro e de todas as maneiras possíveis. Por exemplo, caso um ponto da aplicação passe a ter acesso remoto ao invés de acesso local, isso pode modificar uma outra parte da aplicação, reduzindo seu desempenho e deixando-a mais lenta. Esse tipo de análise não costuma ser feita quando se pensa no design, já que o design tem uma preocupação mais local. Desse modo, essa visão mais global do sistema, é dado o nome de arquitetura (SILVEIRA et al., 2011; PRESSMAN, 2021).

Até o próximo!
😎 

**Referências**:
- PRESSMAN, R. S.; MAXIM, B. R. Engenharia de software-9. McGraw Hill Brasil, [s. l.], 2021.
- SILVEIRA, P. et al. Introd. à Arquitetura e Design de Software: uma visão sobre a plataforma Java. SP: Campus–Elsevier, 2011.
- SOMMERVILLE, I. Engenharia de Software. 10. ed. SP: Pearson, 2018.
