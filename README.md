# 📊 Painel Analítico de Apuração & IA - Eleições 2026

Projeto em Python focado na análise e clusterização de dados do 2º Turno Presidencial das Eleições de 2026. O sistema processa os dados reais e utiliza o algoritmo de Machine Learning **K-Means** para agrupar as unidades federativas de acordo com o comportamento eleitoral e o volume de votos.

---

## 🚀 Acesse o Aplicativo em Tempo Real

Clique no link abaixo para interagir com o Dashboard diretamente pelo seu navegador:
👉 **[CLIQUE AQUI PARA ABRIR O DASHBOARD WEB](COLE_AQUI_O_LINK_DO_SEU_APP)**

---

## 📸 Demonstração do Dashboard

Aqui estão os registros do painel interativo em execução com os gráficos responsivos e a tabela de inteligência artificial:

<p align="center">
  <img src="eleições.jpeg" width="100%" alt="Visão Geral do Painel">
  <br><em>Visão geral das métricas consolidadas e distribuição de votos por estado.</em>
</p>

<p align="center">
  <img src="eleições1.jpeg" width="100%" alt="Análise de Clusters da IA">
  <br><em>Algoritmo K-Means dividindo os estados em grupos estratégicos de comportamento político.</em>
</p>

<p align="center">
  <img src="eleições2.jpeg" width="100%" alt="Tabela Dinâmica de Dados">
  <br><em>Base de dados filtrada e classificada pelo modelo de Machine Learning.</em>
</p>

---

## 🛠️ Tecnologias Utilizadas

- **Streamlit**: Criação do Dashboard interativo e interface web.
- **Scikit-Learn**: Aplicação do algoritmo de Machine Learning K-Means.
- **Plotly**: Geração de gráficos dinâmicos e responsivos.
- **Pandas**: Manipulação, limpeza e tratamento dos dados eleitorais.

---

## 🚀 Como Rodar o Projeto Localmente

1. **Clone o repositório ou baixe os arquivos** na sua máquina.
2. **Instale as dependências necessárias** executando o comando abaixo no terminal:
   ```bash
   pip install -r requirements.txt
   ```
3. **Inicie o painel interativo** com o comando:
   ```bash
   python -m streamlit run dashboard_elecoes.py
   ```
