# Análise Exploratória com MongoDB e Python

Este projeto realiza uma análise exploratória de dados financeiros armazenados em uma base MongoDB, utilizando Python, Pandas, Seaborn, Matplotlib e Jupyter Notebook.

## Tecnologias e dependências

Para executar o projeto, é necessário instalar as dependências listadas no arquivo `requirements.txt`:

Além disso, é necessário instalar o Jupyter para executar o notebook interativo.

---

## Como executar o projeto

Siga os passos abaixo para configurar o ambiente:

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Crie e ative um ambiente virtual Python

No Linux/macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

No Windows:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Instale o Jupyter Notebook e registre o kernel

```bash
pip install notebook ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"

```

### 5. Execute o notebook

Se estiver usando VS Code, basta abrir o arquivo data_analysis.ipynb. O VS Code detecta o Jupyter e você pode clicar em "▶ Run All" ou rodar célula por célula.
