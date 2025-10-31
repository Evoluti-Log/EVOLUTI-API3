# 📌 MVP - Desenvolvimento de um dashboard interativo com dados agregados de segurança viária, permitindo análises comparativas entre estados e indicadores de risco em todo o território nacional

## 🎯 Objetivo do MVP
- O objetivo deste MVP é desenvolver uma ferramenta que integre dados públicos provenientes de diferentes fontes — PRF, DATASUS, DENATRAN e IBGE — para analisar de forma abrangente os indicadores de sinistralidade no trânsito no Brasil. A proposta do MVP é unificar essas bases em uma única plataforma, permitindo a visualização de métricas por estado e em nível nacional.

- Ao centralizar e facilitar o acesso a esses indicadores, o sistema visa aprimorar a compreensão sobre os fatores que influenciam a sinistralidade e contribuir para ações mais eficazes de prevenção e redução de acidentes.
  
- A hipótese que será validada com o MVP é que a integração de múltiplas bases públicas de dados em uma plataforma de BI facilita a análise e interpretação das informações sobre sinistros de trânsito, promovendo maior eficiência na elaboração de políticas públicas e estratégias de segurança viária. 

---

## 📝 Descrição da Solução
- Nesta sprint será desenvolvido o BI de Sinistralidade no Trânsito, com foco na integração e consolidação dos dados das bases PRF e RENAEST. As atividades incluem a importação, limpeza e padronização das informações, criação do modelo de dados relacional e definição de ligação entre acidentes e vítimas. Também serão geradas as métricas e visualizações no Power BI, como número de acidentes, vítimas por tipo e distribuição por UF e rodovia.

- Ao final da sprint, espera-se obter um protótipo funcional e validado do BI, capaz de cruzar dados das diferentes fontes e oferecer uma visão dos principais indicadores de sinistralidade.

---

## 👥 Personas / Usuários-Alvo
- Analista de dados: Representado pelo coodernador Marcus Vinícius Nascimento

- Gestor do projeto: Representado por Carlos Bastos 

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1    | Como analista de dados, quero importar os dados da PRF e RENAEST para o ambiente de BI, para iniciar a consolidação.                                                                 | Alta          | 8 |
| US2    | Como analista, quero tratar e limpar os dados faltantes e valores atípicos, para garantir a qualidade das análises.                                              | Alta          | 5      |
| US3    | Como analista de dados, quero criar o modelo relacional entre as tabelas para permitir cruzamento entre acidentes e vítimas.  | Média         | 5     |
| US4    |  Como analista, quero criar dimensões de tempo (ano, mês, dia) para análises temporais.| Média| 8     |
| US5    | Como gestor de segurança, quero visualizar o número de acidentes por tipo e UF.| Alta          | 8  |                     

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | [Funcionalidade X, Y]                        | Concluído|
| 02     | [Funcionalidade Z]                           | Em andamento |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário [ação principal]  
- O sistema deve registrar [evento importante]  
- Métricas coletadas: [exemplo: tempo de resposta, taxa de uso]  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
