# Conceito, Tipos e Classificação de Requisitos.
>[!Note]
>Resumo 21, Especialização em Eng. de Software por Bruno Rijo

Um **requisito** é tudo aquilo que é preciso para que um software funcione, e são determinados na fase de aquisição ou análise, são utilizadas técnicas para saber quais os requisitos e ideias de software que iriam auxiliar os processos diários do cliente.

Na literatura é bastante comum encontrar várias nomenclaturas diferentes que citam tipos diferentes de requisitos como requisitos de usuário, requisitos de desempenho, requisitos operacionais, etc, etc, etc, mas não é bem assim.

Existem apenas três tipos de requisitos: Requisitos Funcionais, Requisitos Não Funcionais e Requisitos de Negócio ou Organizacionais.

## **Requisito Não Funcional**: 
  É tudo aquilo que é preciso para que os requisitos funcionais sejam executados corretamente. Exemplo: Hardware, sistema operacional, capacidade de armazenamento .. etc

Podem ser classificados como:
- 🔸 De Desempenho
Se referindo a velocidade, confiabilidade e capacidade do sistema. Exemplo: O sistema não deve ultrapassar 2 segundos em qualquer interação com o usuário.
- 🔸 Operacional
Refere-se ao ambiente físico no qual o sistema será instalado. Exemplo:
O sistema deve ser capaz de se integrar com o sistema de outro setor X.
- 🔸 Segurança
Trata das questões de controle de acesso. Exemplo: Apenas os gerentes podem ter acesso ao menu X.

## Requisitos funcionais
São as funcionalidades do software. São as telas que vão compor o software a ser desenvolvido, o conjunto de todos os requisitos são necessários para que a ideia do cliente seja “traduzida” para um sistema de informação.

Algumas classificações são:
- 🔸 **De Usuário**:
Descrevem as ações do software para uma possível interação entre ele e o usuário. Exemplo: O Sistema deve conter uma tela de cadastro de Produtos.
- 🔸 **De Sistema**:
Detatalham os requisitos de usuário, que podem ser validações ou regras de negócio. Exemplos: O sistema deve verificar se o campo X possui apenas letras. / O Sistema deve validar o CPF após o botão “consulta” ser clicado.
- 🔸 **Orientado a Processos**:
Tratam de processos que o software deve executar. Exemplo: O sistema deve permitir que os alunos vejam a programação do curso em que estão matriculados.
- 🔸 **Orientado a Informações**:
Detalha as informações que o sistema deve conter. Exemplo: O Sistema deve guardar o histórico de pedidos do cliente por três anos.

## Requisitos de Negócio ou Organizacionais
São as normas e diretrizes das empresas ou departamentos/setores/seções das empresas, que serão materializadas regras de negócio de um software. Como fatores culturais, missão, valores, leis, decretos.
Exemplo: As informações pessoais estão protegidas segundo as prescrições do Banco Central.

Até a próxima!!

**Referências**:

  - PRESSMAN, R. S. Engenharia de software: uma abordagem profissional. Tradução de João Eduardo Nóbrega Tortello. 8. ed. Porto Alegre: AMGH, 2016.
  - Làbamca, Prìscila. L113e Engenharia de requisitos / Prìscila Làbamca. – Londrina: Editora e Distribuidora Educacional S.A., 2020.
