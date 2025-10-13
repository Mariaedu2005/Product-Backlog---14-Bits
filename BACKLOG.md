# ✈️ Product Backlog – Dashboard de Exportação e Importação do Setor Aeronáutico

## 🧭 Contexto do Projeto
Este projeto tem como objetivo desenvolver um **dashboard interativo** que apresente dados de **exportação e importação do setor aeronáutico brasileiro**, permitindo que o cliente visualize indicadores, tendências e insights estratégicos.

Metodologia: **Scrum** 
Ferramentas: Power BI, Excel, Google Colab(para tratamento).

---

## 🧩 Épico 1 — Coleta e Tratamento de Dados

### 🧱 História 1.1
**Como analista**, quero **coletar dados de exportação e importação do setor aeronáutico** para que o dashboard utilize informações reais e atualizadas.  
**Critérios de aceitação:**
- Fontes de dados identificadas (ex: MDIC, Comex Stat, IBGE, etc.)
- Dados brutos armazenados em formato `.csv` ou `.xlsx` no repositório
- Documentação da origem e data da coleta

### 🧱 História 1.2
**Como desenvolvedora**, quero **tratar e limpar os dados** para garantir que as informações estejam consistentes e sem duplicidade.  
**Critérios de aceitação:**
- Dados padronizados (nomes, unidades, datas)
- Remoção de inconsistências e valores nulos
- Código/script de tratamento documentado

---

## 📊 Épico 2 — Desenvolvimento do Dashboard

### 🧱 História 2.1
**Como cliente**, quero **visualizar indicadores gerais** (total exportado e importado, saldo comercial, países parceiros principais) para entender o panorama do setor.  
**Critérios de aceitação:**
- KPIs visíveis na tela inicial  
- Atualização automática com nova base de dados  
- Design limpo e responsivo  

### 🧱 História 2.2
**Como usuário**, quero **ver gráficos de evolução temporal** das exportações e importações ao longo dos anos.  
**Critérios de aceitação:**
- Gráficos de linha ou barras com período selecionável  
- Filtros por ano, país e tipo de produto aeronáutico  

### 🧱 História 2.3
**Como gestor**, quero **comparar o desempenho por cidade ou estado** para identificar regiões líderes na produção.  
**Critérios de aceitação:**
- Mapa interativo ou gráfico de barras por estado  
- Legenda clara e unidades padronizadas  

### 🧱 História 2.4
**Como analista**, quero **baixar relatórios resumidos em PDF/Excel** com os dados filtrados no dashboard.  
**Critérios de aceitação:**
- Botão de exportação funcional  
- Arquivo gerado contém data e filtros aplicados  

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

## 🗂️ Organização do Repositório (Sugestão)

