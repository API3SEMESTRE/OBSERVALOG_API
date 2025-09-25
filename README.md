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
| Team Member  | Anne Beatriz          | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](linkedin.com/pollyana-dias) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/PollyanaMDS)     |

# Objetivo do Projeto
Desenvolvimento de um dashboard interativo com dados agregados de segurança viária, que integre diferentes bases de dados públicas — PRF, DATASUS, DENATRAN e IBGE — para analisar os indicadores de sinistralidade no trânsito. O sistema deve apresentar métricas por estado e nacionalmente, como: mortalidade, severidade dos sinistros, índice de motorização, frota, população, uso de motocicletas, entre outros.

## Tecnologias Utilizadas

 ### Tecnologias Específicas/Apoio
 > Python
  
 ### Tecnologias da Informação
 > Jira;
 > GitHub;
 > Google Colab;

# Backlog do produto

## Sprint 1
### Tratamento dos Dados
- [X] Normalização e análise inicial dos dados no Google Colab;
- [X] Limpeza inicial utilizando o Google Colab em linguagens de programação Phyton3+, para garantir consistência no dashboard;
### Análise dos Dados
- [X] Primeira versão do dashboard usando a base geral do Renaest, para começar a análise de forma consistente;
- [X] Dashboard no Power BI com interface para visualizar os indicadores de forma intuitiva.
- [X] Dados apresentados em gráficos, para facilitar a interpretação e análise.
### Segmentação dos Dados
- [X] Visualizar os dados por estado, por município e por rodovia, para comparar diferentes níveis de abrangência.
- [X] Filtros interativos e exportação dos dados, para explorar diferentes cenários e compartilhar informações quando necessário.

## Sprint 2
### Estudos Segmentados
- [ ] Visualizar das taxas de mortalidade por 100 mil habitantes em cada estado, para comparar os riscos regionais e gravidades dos acidentes;
- [ ] Acompanhar a evolução histórica dos indicadores, para identificar tendências ao longo do tempo;
- [ ] Segmentar os dados por tipo de veículo, região, ano e gravidade do sinistro para analisar os sinistros mais recorrentes.
### Análises por Estados
- [ ] Desenvolver um um ranking destacando os estados com maior e menor número de mortes, para facilitar comparações visuais.
- [ ] Quais estados tiveram maior eficiência na redução de mortes no trânsito?
- [ ] Possibilidade de monitorar indicadores e apoiar decisões, para melhorar a gestão da segurança viária;
- [ ] Sistema responsivo, adaptável a diferentes dispositivos;

## Sprint 3
### Análise Quantitativa
- [ ] Desenvolver de um ranking de eficiência dos municípios de SP com mais de 100 mil habitantes, considerando frota, população, orçamento municipal e quantidade de sinistros, para avaliar e comparar a eficiência municipal;
### Estudo de Sazonalidade
- [ ] Visualizar os indicadores de mortalidade, sazonalidade dos acidentes (mensal, semanal, diária e horária), tipos de veículos envolvidos e tamanho da frota por município, para ter uma visão completa da situação;
### Segmentação da frota
- [ ] Aplicar filtros por tipo de veículo (carros, motos, caminhões), para analisar quais contribuem mais para os sinistros.;
      
# Registro das Sprints

|  Sprint | Previsão | Status  |
|---------|----------|---------|
|01 | 30/09/2025 | Concluido | 
|02|  20/10/2025 | a fazer |
|03| 17/11/2025 | a fazer| 
|Feira de Soluções| 04/12/2025 |a fazer |
