# Modelo de Segurança SDL
>[!Note]
>Resumo 39, Especialização em Eng. de Software por Bruno Rijo

Foram criados alguns modelos com a intenção guiar, auxiliar e reforçar a segurança do produto que é projetado e desenvolvido, em todo o processo de desenvolvimento. O uso desses modelos pelas empresas, visa desempenhar boas práticas de desenvolvimento, com foco na qualidade e segurança da aplicação, além de contribuir para que novos modelos sejam criados através de aprimoramento, fruto de observação de como esse modelo é usado.

O Modelo SDL, que vem de Security Development Lifecycle, foi desenvolvido em 2002 pela Microsoft e utilizado na implementação das suas aplicações. É um modelo utilizado que propõe modificar a maneira como o software é habitualmente desenvolvido, tendo como resultado um produto com alto padrão de segurança. 

Alguns aspectos importantes desse modelo merecem ser destacados, como:
- Criação de modelos de ameaças durante o design do software
- Uso de ferramentas de verificação do código de análise estática durante a codificação.
- Revisões e testes de segurança

Nessa perspectiva, podemos determinar que o modelo compõe uma série de atividades, que merecem atenção especial, segundo De Win et al. (2009): o aumento da qualidade, com foco na segurança das funcionalidades; os processos que são definidos em estágios distribuídos ao longo da fase de criação; a facilidade nas orientações a serem seguidas, já que o método é simples de ser compreendido; e, por fim, a descrição das atividades.

As fases a serem seguidas durante a execução do modelo SDL são as seguintes:
1. **Treinamento**: São aplicados treinamentos para a equipe, sobre temas que compreendem: desenho seguro para redução da superfície de ataque; defesa em profundidade; privilégio mínimo; defaults seguros; modelagem de ameaças; codificação segura; teste de segurança e questões relacionadas à privacidade de informações pessoais.
2. **Requisitos**: São estabelecidos requisitos de segurança e rastreamento de bugs, que deve elencar suas causas ou origem do defeito.
3. **Design**: Nessa fase devem ser estabelecidos requisitos de design, analisadas superfícies de segurança e montadas modelagem de ameaças.
4. **Implementação**: A recomendação para essa fase é o uso de ferramentas aprovadas e análise estática para identificar possíveis  vulnerabilidades
5. **Verificação**: Nessa fase são feitos testes, inspeçoes e código e análise dos documentos produzidos. Recomenda-se o uso de ferramentas automatizads.
6. **Liberação**: Deve ser feita uma revisão de segurança, bem como um plano de resposta de incidentes.
7. **Resposta**: Execução do plano de resposta de incidentes.

Para uma boa execução desse modelo em todas as fases é importante manter uma equipe alinhada com o modelo, e ter ciência de que o seu uso favorece boas práticas de criação da aplicação em todo o processo.

Até o próximo. :)
