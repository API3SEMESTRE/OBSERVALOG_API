<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=FFFF99&height=120&section=header&text=OBSERVALOG&fontColor=000000&fontSize=40&fontAlignY=35"/>

# Aprendizado por Projeto Integrador (API)

O Aprendizado por Projeto Integrador é uma metodologia que conecta teoria e prática, permitindo que os alunos trabalhem em equipe no desenvolvimento de projetos que envolvem diferentes áreas do conhecimento. A proposta incentiva a aplicação de conceitos aprendidos ao longo do curso para resolver problemas reais, além de estimular competências como colaboração, autonomia, proatividade e foco em resultados, especialmente quando associado a metodologias ágeis como o SCRUM.

# Índice
* [Projeto](#projeto-template)
* [Equipe](#Equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Backlog do produto](#Backlog-do-produto)
* [Sprints](#Sprints)

# Projeto (API) 
O projeto tem como objetivo desenvolver uma ferramenta de Business Intelligence que integre diferentes bases de dados públicas — PRF, DATASUS, DENATRAN e IBGE — a fim de analisar de forma abrangente os indicadores de sinistralidade no trânsito brasileiro. A proposta envolve a construção de painéis interativos que apresentem métricas em nível estadual e nacional, contemplando indicadores como mortalidade, severidade dos sinistros, índice de motorização, frota de veículos, população e uso de motocicletas. Reunindo e conectando dados de diferentes fontes, o estudo pretende contribuir para o aprimoramento de políticas públicas e estratégias de gestão voltadas à segurança viária no Brasil.

# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Anna Luiza        |    [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/annaluizalrc/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/annaluizalrc)              |
| Scrum Master |   Júlia Satlher       |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/j%C3%BAlia-satlher/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/jurlhn)                |
| Team Member |   Júlia Caraça       |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/julia-caraca-de-sousa/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/juliacaraca)               |
| Team Member  | Pollyana Dias          |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](linkedin.com/pollyana-dias) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/PollyanaMDS)     |
| Team Member  | Daniel Pontes          |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](linkedin.com/pollyana-dias) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/PollyanaMDS)     |
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


># Product Backlog

| Rank | Prioridade | User Story                                                                                                                                              | Esforço | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
| 1    | Alta       | Como analista/gestor, quero que os dados coletados passem por uma limpeza inicial em linguagens de programação, para garantir consistência no dashboard.                                                    | 5          | 1      |
| 2    | Alta       | Como gestor/analista, quero que a primeira versão do dashboard use a base geral do Renaest, para começar a análise de forma consistente.                                                                  | 8          | 1      |
| 3    | Alta       | Como analista/gestor, quero acessar o dashboard no Power BI com interface para visualizar os indicadores de forma intuitiva.                                                          | 8          | 1      |
| 4    | Média       | Como gestor/analista, quero ter os dados apresentados em gráficos, para facilitar a interpretação e análise.                                                    | 8          | 1      |
| 5    | Média       | Como gestor/analista, quero visualizar os dados por estado para comparar diferentes níveis de abrangência.                                                                    | 8          | 1      |
| 6    | Baixa       | Como gestor/analista, quero filtros interativos e exportação dos dados, para explorar diferentes cenários e compartilhar informações quando necessário.                                                          | 8          | 1      |
| 7    | Alta       | Como analista/gestor, quero visualizar taxas de mortalidade por 100 mil habitantes em cada estado, para que eu possa comparar os riscos regionais e gravidades dos acidentes.                                                    | 8          | 2      |
| 8    | Alta       | Como analista/gestor, quero um ranking destacando os estados com maior e menor número de mortes, para facilitar comparações visuais.                                                                    | 8          | 2      |
| 9    | Alta       | Como analista/gestor, quero visualizar quais estados tiveram maior eficiência na redução de mortes no trânsito.                                                         | 8          | 2      |
| 10    | Média       | Como gestor/analista, quero acompanhar a evolução histórica dos indicadores, para identificar tendências ao longo do tempo.                                                | 13          | 2      |
| 11    | Média       | Como analista/gestor, quero segmentar os dados por tipo de veículo, região, ano e gravidade do sinistro para analisar os sinistros mais recorrentes.                                                                    | 8          | 2      |
| 12    | Baixa       | Como gestor/analista, quero monitorar indicadores e apoiar decisões, para melhorar a gestão da segurança viária.                                                           | 13          | 2      |
EDITAR A SPRINT 3| 13    | Alta       | Como gestor, quero um ranking de eficiência dos municípios de SP com mais de 100 mil habitantes, considerando frota, população, orçamento municipal e quantidade de sinistros, para avaliar e comparar a eficiência municipal.                                                    | 8          | 3      |
| 14    | Alta       | Como gestor/analista, quero visualizar os indicadores de mortalidade, sazonalidade dos acidentes (mensal, semanal, diária e horária), tipos de veículos envolvidos e tamanho da frota por município, para ter uma visão completa da situação.                                                                    | 13          | 3      |
| 15    | Média       | Como analista/gestor, quero aplicar filtros por tipo de veículo (carros, motos, caminhões), para analisar quais contribuem mais para os sinistros.                                                           | 21          | 3      |

                                                   
# Registro das Sprints

|  Sprint | Previsão | Status  |
|---------|----------|---------|
|01 | 30/09/2025 | Concluído | 
|02|  20/10/2025 | Concluído |
|03| 17/11/2025 | em andamento | 
|Feira de Soluções| 04/12/2025 |a fazer |

# Registro das Sprints

| Sprint            | Previsão   | Status   | Histórico |
|-------------------|------------|----------|-----------|
| 01                | dd/mm/aaaa | a fazer  | [MVP](MVP/sp1.md)  |
| 02                | dd/mm/aaaa | a fazer  | [MVP](MVP/sp2.md)  |
| 03                | dd/mm/aaaa | a fazer  | [MVP](MVP/sp3.md)  |
| Feira de Soluções | dd/mm/aaaa | a fazer  | [MVP](#)  |







# Backlog do produto

## Sprint 1

<img width="2261" height="550" alt="image" src="https://github.com/user-attachments/assets/85fdb977-bf97-4da9-b132-4b169d750a74" />

## Resultado 
[Assista ao vídeo no YouTube](https://youtu.be/WY0kTnESSbU)

## Sprint 2

<img width="2261" height="747" alt="image" src="https://github.com/user-attachments/assets/d05990c1-ae30-4111-84bc-ff7f84779b55" />

## Resultado 
[Assista ao vídeo no YouTube](https://www.youtube.com/watch?v=EZbInjI3f28)

## Sprint 3

<img width="2261" height="461" alt="image" src="https://github.com/user-attachments/assets/b2456478-7b26-4fe3-b184-e0bbaf960773" />



