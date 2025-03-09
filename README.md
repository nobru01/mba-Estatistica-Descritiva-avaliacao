# Análise Estatística SINAPI

## Descrição
Este projeto contém análises estatísticas descritivas dos dados do SINAPI (Sistema Nacional de Pesquisa de Custos e Índices da Construção Civil), incluindo visualizações e análises temporais dos custos de construção civil no Brasil.

## Pré-requisitos
- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)
- Jupyter Notebook ou JupyterLab

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/nobru01/mba-Estatistica-Descritiva-avaliacao.git
cd estatistica-descritiva
```

2. Crie um ambiente virtual (recomendado):
```bash
# No Windows
python -m venv venv
venv\Scripts\activate

# No Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

## Executando o Notebook

1. Ative o ambiente virtual (se não estiver ativado):
```bash
# No Windows
venv\Scripts\activate

# No Linux/Mac
source venv/bin/activate
```

2. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

3. No navegador, abra o arquivo `sinapi.ipynb`

## Estrutura do Projeto
estatistica-descritiva/
│
├── README.md
├── requirements.txt
├── sinapi.ipynb
└── venv/

## Análises Incluídas
- Estatísticas descritivas dos custos
- Análise temporal
- Correlogramas
- Análise de cointegração
- Visualizações:
  - Gráficos de barras
  - Gráficos de linha
  - Heatmaps
  - Violin plots

## Problemas Comuns

### ModuleNotFoundError
Se encontrar erro de módulo não encontrado:
```bash
pip install -r requirements.txt --upgrade
```

### Erro no Jupyter
Se o kernel não iniciar:
```bash
python -m ipykernel install --user
```

## Contribuindo
1. Fork o projeto
2. Crie sua branch de feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request



## Contato
Seu Nome - brunoferreira01@gmail.com