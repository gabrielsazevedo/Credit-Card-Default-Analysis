# Credit Default Analysis Project

## Project Description
A credit risk analysis project using machine learning techniques to predict credit card default probability.

## Project Structure
```
credit_default_analysis/
├── dataset_source/
│   └── default_of_credit_card_clients.xls
├── src/
│   ├── data/
│   │   └── data_loader.py
│   ├── preprocessing/
│   │   └── preprocessor.py
│   ├── models/
│   │   ├── base_model.py
│   │   ├── svm_model.py
│   │   └── random_forest_model.py
│   ├── visualization/
│   │   └── visualizer.py
│   └── utils/
│       └── metrics.py
├── main.py
└── requirements.txt
```

## Requirements
- Python 3.8+
- Libraries:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
  - openpyxl

## Installation

1. Clone the repository:
```bash
git clone https://github.com/{your-username}/credit-default-analysis.git
cd credit-default-analysis
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
```bash
python main.py
```

## Features
- Excel file data loading
- Data preprocessing
- Model training:
  - Support Vector Machine (SVM)
  - Random Forest
- Performance metrics generation
- Visualizations:
  - Metrics comparison
  - Confusion matrices
  - Feature importance analysis

## Methodology
1. Data loading
2. Preprocessing
3. Train-test data split
4. Model training
5. Performance evaluation
6. Result visualization

## Contributing
1. Fork the project
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## Contact
Gabriel Azevedo - gabriel.azeve04@gmail.com

## References
- Dataset: UCI Machine Learning Repository
- Scikit-learn Documentation
- Pandas Documentation

-------------------------------------

# Credit Default Analysis Project

## Descrição do Projeto
Um projeto de análise de risco de crédito utilizando técnicas de machine learning para prever a probabilidade de inadimplência em cartões de crédito.

## Estrutura do Projeto
```
credit_default_analysis/
├── dataset_source/
│   └── default_of_credit_card_clients.xls
├── src/
│   ├── data/
│   │   └── data_loader.py
│   ├── preprocessing/
│   │   └── preprocessor.py
│   ├── models/
│   │   ├── base_model.py
│   │   ├── svm_model.py
│   │   └── random_forest_model.py
│   ├── visualization/
│   │   └── visualizer.py
│   └── utils/
│       └── metrics.py
├── main.py
└── requirements.txt
```

## Requisitos
- Python 3.8+
- Bibliotecas:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
  - openpyxl

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/{seu-usuario}/credit-default-analysis.git
cd credit-default-analysis
```

2. Crie um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

## Uso
```bash
python main.py
```

## Funcionalidades
- Carregamento de dados de arquivos Excel
- Pré-processamento de dados
- Treinamento de modelos:
  - Support Vector Machine (SVM)
  - Random Forest
- Geração de métricas de desempenho
- Visualizações:
  - Comparação de métricas
  - Matrizes de confusão
  - Importância de features

## Metodologia
1. Carregamento de dados
2. Pré-processamento
3. Divisão de dados de treino e teste
4. Treinamento de modelos
5. Avaliação de desempenho
6. Visualização de resultados

## Contribuição
1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## Contato
Gabriel Azevedo - gabriel.azeve04@gmail.com

## Referências
- Dataset: UCI Machine Learning Repository
- Scikit-learn Documentation
- Pandas Documentation
```
