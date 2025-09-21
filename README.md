<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=FFFF99&height=120&section=header&text=OBSERVALOG&fontColor=000000&fontSize=40&fontAlignY=35"/>

# Aprendizado por Projeto Integrador (API)

O Aprendizado por Projeto Integrador é uma metodologia que conecta teoria e prática, permitindo que os alunos trabalhem em equipe no desenvolvimento de projetos que envolvem diferentes áreas do conhecimento. A proposta incentiva a aplicação de conceitos aprendidos ao longo do curso para resolver problemas reais, além de estimular competências como colaboração, autonomia, proatividade e foco em resultados, especialmente quando associado a metodologias ágeis como o SCRUM.

# Índice
* [Projeto](#projeto-template)
* [Equipe](#Equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Sprints](#Sprints)
* [Burndown](#Burndown)
* [Backlog do produto](#Backlog-do-produto)

# Projeto (API) 
O projeto tem como objetivo desenvolver uma ferramenta de Business Intelligence que integre diferentes bases de dados públicas — PRF, DATASUS, DENATRAN e IBGE — a fim de analisar de forma abrangente os indicadores de sinistralidade no trânsito brasileiro. A proposta envolve a construção de painéis interativos que apresentem métricas em nível estadual e nacional, contemplando indicadores como mortalidade, severidade dos sinistros, índice de motorização, frota de veículos, população e uso de motocicletas. Reunindo e conectando dados de diferentes fontes, o estudo pretende contribuir para o aprimoramento de políticas públicas e estratégias de gestão voltadas à segurança viária no Brasil.

# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Anna Luiza        |    [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/annaluizalrc/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/annaluizalrc)              |
| Scrum Master |   Júlia Satlher       |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/j%C3%BAlia-satlher/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/jurlhn)                |
| Team Member |   Júlia Caraça       |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/julia-caraca-de-sousa/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/juliacaraca)               |
| Team Member  | Pollyana Dias          |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](linkedin.com/pollyana-dias) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/PollyanaMDS)     |
| Team Member  | Daniel Montes          |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](linkedin.com/pollyana-dias) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/PollyanaMDS)     |
|  Team Member  | Anne Beatriz                 |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/anne-beatriz-abba402b7?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) [![GitHub Badge](https://img.shields.io/badge/GitHsquare&logo=github&logoColor=white)](https://github.com/Anneolivi)           |


# Objetivo do Projeto
Desenvolvimento de um dashboard interativo com dados agregados de segurança viária, que integre diferentes bases de dados públicas — PRF, DATASUS, DENATRAN e IBGE — para analisar os indicadores de sinistralidade no trânsito. O sistema deve apresentar métricas por estado e nacionalmente, como: mortalidade, severidade dos sinistros, índice de motorização, frota, população, uso de motocicletas, entre outros.

## Tecnologias Utilizadas

 ### Tecnologias Específicas/Apoio
 > Python
  
 ### Tecnologias da Informação
 > Jira;
 > GitHub;

# Backlog do produto

## Sprint 1
### Análise comparativa regional 
- [ ] Como o desempenho comercial de um Estado se compara aos outros?
- [ ] Segmentação por Estado;
- [ ] Apresentar dados detalhados sobre exportação, a partir da segmentação;
- [ ] Normalização e análise inicial dos dados no Google Colab;
- [ ] A partir ds dados no Google Colab, utilizar bases públicas de comércio exterior,
com código reutilizável para futuras análises no Power BI;
### Identificação de mercados emergentes
- [ ] Identificar quais países têm aumentado a importação de produtos específicos de cada Estado brasileiro;
- [ ] Buscar e filtrar para pesquisa de cargas e análise específica;
- [ ] Desenvolvimetno do back-end em Python 3+;

## Sprint 2
### Geografia dos fluxos
- [ ] Identificar em quais localidades (Unidades de Receita Federal) são processadas as exportações de cada Estado;
- [ ] Desenvolver um painel de Estatísticas interativo, exibindo a balança comercial de 2022 a 2024;
- [ ] Desenvolver o front-end no Power BI;
### Diversificação de produtos
- [ ] Detectar se os estados concentram suas exportações em poucos produtos ou apresentam uma pauta diversificada;
- [ ] Utilizar o GitHub para controle de versão dos artefatos do projeto;
### Análises de vias de transporte
- [ ] Pesquisar quais são os principais modais de transporte utilizados para escoar exportações em nível internacional;
- [ ] Sistema responsivo, adaptável a diferentes dispositivos;

## Sprint 3
### Estudo de Sazonalidade
- [ ] Descobrir se existem padrões sazonais nas exportações de determinados produtos;
- [ ] Pesquisar como as empresas locais lidam com as variações;
### Análise de Tendência e Projeção 
- [ ] Identificar quais as tendências de exportação;
- [ ] Detectar a possibilidade de criação de um modelo de projeção futura;
### Análise de Risco
- [ ] Descobrir quais os riscos associados à dependência de mercados específicos ou de poucos parceiros comercias;
      
## Sprint 4
- [ ] Visualizar os principais países de destino das exportações;
- [ ] Demonstrar comparações entre destinos e modais utilizados;
- [ ] Analisar a eficiência logística de diferentes mercados;
- [ ] Vizualizar oportunidades de otimização para novos mercados;


# Registro das Sprints

|  Sprint | Previsão | Status  |
|---------|----------|---------|
|01 | 29/09/2025 | a fazer | 
|02|  20/10/2025 | a fazer |
|03| 17/11/2025 | a fazer| 
|Feira de Soluções| 04/12/2025 |a fazer |
