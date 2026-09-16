# Análise Tática de Sinistros de Trânsito nas Rodovias Federais (TP2)

Este repositório contém o Notebook de Ciência de Dados desenvolvido para a análise, segmentação e classificação de acidentes nas rodovias federais brasileiras, utilizando técnicas de aprendizado de máquina (K-Means e KNN).

## 📊 Fonte dos Dados
Os dados originais utilizados neste projeto são de domínio público e fornecidos oficialmente pelo Governo Federal do Brasil. Para garantir a total reprodutibilidade do código por parte dos avaliadores, os arquivos exatos (com o recorte temporal utilizado) foram disponibilizados via Google Drive.

*   **Organização Responsável:** Polícia Rodoviária Federal (PRF) - Ministério da Justiça e Segurança Pública.
*   **Arquivos Utilizados:** `datatran2025.csv` e `acidentes2025.csv`.
*   **Fonte Oficial:** [Portal de Dados Abertos da PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-acidentes)
*   **Links Diretos para Download (Arquivos do Projeto):**
    *   [`datatran2025.csv` - Baixar via Google Drive](https://drive.google.com/file/d/1-G3MdmHBt6CprDwcW99xxC4BZ2DU5ryR/view)
    *   [`acidentes2025.csv` - Baixar via Google Drive](https://drive.google.com/file/d/1-Gp9S-ALO0D1nT8S_OKoC8xlW7BY8F82/view)
*   **Data de Download Original:** 15 de setembro de 2026

> **Nota:** A citação formal desta base de dados, em formato BibTeX, encontra-se na seção de Referências Bibliográficas ao final do relatório principal.

## 💻 Ambiente de Execução
O projeto foi desenvolvido inteiramente em **Python 3** (recomenda-se versão 3.9 ou superior) utilizando o ecossistema do **Jupyter Notebook**. 

As análises dependem de bibliotecas padrão de manipulação de dados (`pandas`, `numpy`), visualização estática e interativa (`matplotlib`, `seaborn`, `plotly`, `squarify`) e da suíte de aprendizado de máquina `scikit-learn` para as etapas de clusterização e classificação.

## 🚀 Como Executar as Análises

Siga o passo a passo abaixo para garantir a reprodutibilidade do código sem conflitos de versão:

**1. Clone o repositório ou baixe os arquivos**
Certifique-se de que o arquivo de dados (`.csv` da PRF) e o arquivo do notebook (`.ipynb`) estejam no mesmo diretório.

**2. Crie um ambiente virtual (Opcional, mas recomendado)**
Abra o terminal na pasta do projeto e execute:
```bash
python -m venv venv
```

Ative o ambiente:
Windows: venv\Scripts\activate
Linux/Mac: source venv/bin/activate

**3. Instale as dependências** 
Instale todas as bibliotecas necessárias executando:
```bash
pip install -r requirements.txt
```

**4. Execute o Jupyter Notebook**
Inicie o servidor do Jupyter rodando:
```bash
jupyter notebook
```