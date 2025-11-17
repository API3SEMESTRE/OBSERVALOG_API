# 📌 MVP - OBSERVALOG

## 🎯 Objetivo do MVP
O MVP tem como propósito validar a viabilidade e o valor de um dashboard analítico baseado nos dados do Renaest, permitindo que gestores e analistas visualizem indicadores de forma organizada, intuitiva e confiável. 

## ✅Problema que resolve
Atualmente, a análise dos dados do Renaest é prejudicada por:
Falta de padronização e limpeza inicial dos dados
Dificuldade de visualização integrada por estado, nível nacional e por filtros cruzados
Ausência de uma interface amigável que facilite interpretação rápida e tomada de decisão
O MVP resolve isso ao entregar uma primeira versão funcional do dashboard, já com dados limpos, estruturados e organizados.

## ✅Hipótese que será validada
A hipótese do MVP é que um dashboard com dados padronizados, visualizações por estado e recursos básicos de interação melhora a análise e tomada de decisão dos gestores, permitindo identificar tendências, comparar cenários e reduzir o tempo gasto em manipulação de dados.

## ✅Valor entregue ao usuário final
O MVP entrega:
Confiabilidade: dados limpos, tratados e consistentes
Acessibilidade: interface intuitiva no Power BI
Clareza: visualizações nacionais e estaduais que facilitam a interpretação
Agilidade: primeiros filtros e comparações essenciais para análise rápida
Base sólida: estrutura inicial para expansões futuras (mais filtros, mais gráficos, mais análises)

## 📝 Descrição da Solução
O MVP consiste em um dashboard inicial em Power BI, construído a partir de dados limpos e preparados previamente em Python, com foco nas funcionalidades essenciais para validar a proposta.

## 🔧 Funcionalidades principais incluídas
Com base nas sprints concluídas, o MVP inclui:
Limpeza e padronização dos dados
Scripts em Python para organizar e tratar a base Renaest
Garantia de consistência para carregamento no Power BI
Primeira versão do dashboard
Uso da base geral do Renaest para iniciar a análise
Estrutura inicial das tabelas e relacionamentos
Interface limpa e intuitiva no Power BI
Navegação simples
Indicadores principais apresentados de forma visual
Gráficos e mapas descritivos
Tendências por estado
Indicadores principais em gráficos
Visualização comparativa entre estados
Cenário nacional
Comparação entre estados e média nacional
Primeiros filtros interativos
Tipo de veículo
Região
Ano
Fatalidade / gravidade
Filtro cruzado entre saúde e transporte

## ⚠️ Limitações conhecidas do MVP

Filtros avançados ainda não foram incluídos (ex.: multissegmentações complexas)
O dashboard ainda não contempla análises preditivas ou modelos estatísticos
Exportações avançadas de relatórios podem não estar disponíveis
Algumas visualizações podem ser simplificadas para priorizar a validação inicial

## 📌 Escopo reduzido (somente o essencial)

O MVP entrega apenas o necessário para validar a ideia:
Dados limpos
Painel funcional
Visualizações básicas essenciais
Primeiros filtros interativos
Comparação entre estados
Funcionalidades avançadas, detalhamento profundo e análises futuras ficarão para as próximas versões.
---

# 👥 Personas / Usuários-Alvo

---

## 📌 Persona 1 — Gestor de Mobilidade (Tomador de Decisão)

**Descrição:**  
Gestor público responsável por políticas de mobilidade urbana, planejamento de infraestrutura e definição de ações estratégicas. Precisa de informações rápidas, confiáveis e comparativas para embasar decisões.

**Necessidades:**  
- Visualizar rapidamente indicadores-chave sobre segurança no trânsito.  
- Comparar estados e regiões para identificar onde direcionar recursos e ações.  
- Acompanhar tendências de acidentes, mortes e sinistros.  
- Ter dados confiáveis e atualizados sem precisar manipular bases complexas.

**Dores atendidas pelo MVP:**  
- Falta de padronização dos dados → resolvida pela limpeza inicial do MVP.  
- Dificuldade em interpretar informações dispersas → resolvida com o dashboard visual e intuitivo.  
- Tempo gasto para produzir relatórios → reduzido com visualizações prontas e comparações automáticas.  
- Insegurança nos dados → mitigada com base tratada e centralizada.

---

## 📌 Persona 2 — Analista de Dados em Segurança Viária

**Descrição:**  
Profissional técnico que trabalha com análise detalhada de acidentes, mortalidade e fatores de risco. Explora tendências, gera relatórios e busca padrões nos dados.

**Necessidades:**  
- Acessar dados limpos e organizados para análises aprofundadas.  
- Aplicar filtros por tipo de veículo, região, ano, gravidade etc.  
- Identificar anomalias e comportamentos específicos por estado.  
- Exportar dados e gráficos para complementar relatórios internos.

**Dores atendidas pelo MVP:**  
- Dificuldade para trabalhar com dados brutos e inconsistentes → resolvida pela modelagem e limpeza.  
- Falta de filtros e ferramentas para análises específicas → atendidas pelos filtros iniciais do dashboard.  
- Necessidade de cruzar dados de saúde e transporte → viabilizada pelos filtros cruzados.  
- Perda de tempo criando gráficos manualmente → solucionada com visualizações prontas no Power BI.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como analista/gestor, quero que os dados coletados passem por uma limpeza inicial em linguagens de programação, para garantir consistência no dashboard. | Alta       | 5 pontos   |
| US2 | Como gestor/analista, quero que a primeira versão do dashboard use a base geral do Renaest, para começar a análise de forma consistente. | Alta    | 8 pontos   |
| US3 | Como analista/gestor, quero acessar o dashboard no Power BI com interface para visualizar os indicadores de forma intuitiva. | Alta    | 8 pontos   |
| US4 | Como gestor/analista, quero ter os dados apresentados em gráficos, para facilitar a interpretação e análise. | Média    | 8 pontos   |
| US5 | Como gestor/analista, quero visualizar os dados por estado para comparar diferentes níveis de abrangência. | Média    | 8 pontos   |
| US5 | Como gestor/analista, quero filtros interativos e exportação dos dados, para explorar diferentes cenários e compartilhar informações quando necessário. | Média    | 8 pontos   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     |Documentação técnica completa com scripts de limpeza e modelagem em Python.| Concluído|
| 01     |Dados de frota, população, mortes, sinistros.| Concluído |
| 01     |Dashboard em Power BI com interface limpa, navegação intuitiva e dados atualizados.| Concluído|
| 01     |Mapas e gráficos de tendência por estado.| Concluído |
| 01     |Visualização Nacional e Estadual; Comparativo entre estados e média nacional.| Concluído|
| 01     |Filtros Interativos; Segmentação por tipo de veículo, região, ano, gravidade; Filtro cruzado entre saúde e transporte.| Concluído |


---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário **visualize indicadores nacionais e estaduais de forma clara e intuitiva no dashboard**.  
- O sistema deve registrar **as interações realizadas no dashboard, como filtros aplicados e visualizações mais acessadas**.  
- **Métricas coletadas:**  
  - Tempo médio de navegação por página  **5 minutos**
  - Taxa de uso dos filtros (região, tipo de veículo, ano, gravidade)  
  - Número de acessos ao dashboard por período  **8 acessos**

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP  **5 usuários**
- Feedback qualitativo (positivo/negativo)  
- Indicadores de negócio, como:  
  - % de adesão ao uso do dashboard  100%
  - Redução do tempo gasto para gerar relatórios  
  - Aumento na percepção de confiabilidade dos dados  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback dos usuários  
- Ajustes de usabilidade, como aprimoramento de layout e navegação  
- Expansão das funcionalidades para os próximos incrementos, incluindo:  
  - Análises preditivas  
  - Novos painéis segmentados (municípios, faixa etária, tipo de ocorrência)  
  - Integração com novas bases de dados  

---

## 📂 Anexos / Evidências

[Assista ao vídeo no YouTube](https://youtu.be/WY0kTnESSbU)
