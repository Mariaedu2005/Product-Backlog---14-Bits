# ✈️ Product Backlog – Dashboard de Exportação e Importação do Setor Aeronáutico

## 🧭 Contexto do Projeto
Este projeto tem como objetivo desenvolver um **dashboard interativo** que apresente dados de **exportação e importação do setor aeronáutico brasileiro**, permitindo que o cliente visualize indicadores, tendências e insights estratégicos.

Metodologia: **Scrum** 
Ferramentas: Power BI, Excel, Google Colab(para tratamento).

---

## 🧩 Sprint 1 — Coleta e Tratamento de Dados

### 🧱 História 1.1
**Como gestor**, quero **coletar dados de exportação e importação do setor aeronáutico** para que o dashboard utilize informações reais e atualizadas.  
**Critérios de aceitação:**
- Fontes de dados identificadas (Comex Stat)
- Dados brutos armazenados em formato `.csv` ou `.xlsx` no repositório
- Documentação da coleta

### 🧱 História 1.2
**Como gestor**, quero **tratar e limpar os dados** para garantir que as informações estejam consistentes e sem duplicidade.  
**Critérios de aceitação:**
- Dados padronizados
- Remoção de inconsistências e valores nulos
- Achar codígos sh4 do setor aeronáutico

  ### 🧱 História 1.3
  **Como gestor**, quero **desenvolver um dashboard** com o indicador de exportação com filtros e gráficos de visualização.
  **Critérios de aceitação:**
  - Gráficos formatados
  - Filtros de dados por produto/cidade
  - Gráficos mostrando dados do Vale do Paraiba

---

## 📊 Sprint 2 — Desenvolvimento

### 🧱 História 2.1
**Como cliente**, quero **visualizar o indicador de exportação** através dos anos.
**Critérios de aceitação:**
- Usar gráfico de linhas com eixo x mostrando os anos e eixo y mostrando os valores 
- Acrescentar os dados dos produtos em Kg
- Atualizar informações do gráfico

### 🧱 História 2.2
**Como gestor**, quero **adicionar indicadores** mostrando os principais compradores da Embraer e o porquê a Escandinava  
**Critérios de aceitação:**
- Gráficos de linha ou barras com período selecionável  
- Filtros por ano, país e tipo de produto aeronáutico  

### 🧱 História 2.3
**Como gestor**, quero **comparar o desempenho por cidade ou estado** para identificar regiões líderes na produção.  
**Critérios de aceitação:**
- Mapa interativo ou gráfico de barras por estado  
- Legenda clara e unidades padronizadas 

---

## ⚙️ Épico 3 — Infraestrutura e Integração

### 🧱 História 3.1
**Como equipe de desenvolvimento**, quero **armazenar o código e os dados em um repositório GitHub** para controle de versão e colaboração.  
**Critérios de aceitação:**
- Repositório criado e estruturado (`/data`, `/scripts`, `/dashboard`, `/docs`)  
- README explicando objetivo e instruções de uso  

### 🧱 História 3.2
**Como cliente**, quero **acessar a versão online do dashboard** sem precisar instalar programas.  
**Critérios de aceitação:**
- Dashboard publicado no Power BI Service / GitHub Pages / Streamlit  
- Link funcional documentado no README  

---

## 🧠 Épico 4 — Apresentação e Entrega Final

### 🧱 História 4.1
**Como cliente**, quero **assistir à apresentação do projeto** mostrando o funcionamento do dashboard e os principais insights.  
**Critérios de aceitação:**
- Slides ou vídeo demonstrativo criados  
- Script de apresentação preparado  
- Conclusões apresentadas com base nos dados  

### 🧱 História 4.2
**Como equipe**, quero **registrar todo o processo no GitHub** para demonstrar a aplicação da metodologia Scrum.  
**Critérios de aceitação:**
- Issues criadas para cada história de usuário  
- Milestones correspondendo às sprints  
- Histórico de commits limpo e organizado  

---



