# predicao-nitrogenio-amoniacal-tiet04200
O projeto implementa e compara diferentes modelos de aprendizado de máquina para estimar concentrações de nitrogênio amoniacal  no ponto de monitoramento TIET04200, localizado no Rio Tietê e operado pela CETESB. Inclui etapas de pré-processamento, análise exploratória, seleção de variáveis, modelagem, avaliação de métricas e geração de gráficos


# Predição de Nitrogênio Amoniacal (NH₄⁺) no Rio Tietê usando Machine Learning

Repositório contendo o código-fonte desenvolvido para estudo sobre “Machine Learning aplicado à Predição de Nitrogênio Amoniacal para Apoio ao Monitoramento e Gestão de Recursos Hídricos.

O objetivo principal é aplicar e avaliar algoritmos de aprendizado de máquina para prever concentrações de nitrogênio amoniacal (NH₄⁺) na estação **TIET04200**, localizada no Rio Tietê e operada pela **CETESB**, usando dados do período **2019–2025**.

---

🌎 Objetivo do Trabalho

A utilização de modelos preditivos para monitoramento hídrico, especialmente em rios urbanos como o Tietê, permite:

Complementar ações de vigilância ambiental

Antecipar variações críticas da qualidade da água

Apoiar a tomada de decisão em gestão de recursos hídricos

Minimizar custos operacionais de amostragem

📜 Licença

Este projeto está licenciado sob MIT License.
Sinta-se livre para usar, adaptar e referenciar, desde que mantenha os créditos ao autor.


## 📌 Conteúdos do Repositório

- Código em Python para:
  - Pré-processamento dos Dados
  - Análise Exploratória (EDA)
  - Seleção de variáveis e correlações
  - Treinamento e validação de modelos
  - Avaliação por métricas (MAE, MSE, RMSE, R², MAPE, CCC)
  - Geração de gráficos, tabelas e figuras utilizadas no TCC
  

---

## 🧪 Modelos Avaliados

Os principais algoritmos utilizados foram:

- Random Forest  
- XGBoost  
- MLP (Multilayer Perceptron)  
- Regressão Linear


---

## 🗂 Estrutura do Repositório



📁 /data/
└── 
📁 /notebooks/
├── eda.ipynb
├── modelagem.ipynb
└── metricas.ipynb
📁 /scripts/
├── preprocess.py
├── train_models.py
└── eval_metrics.py
📁 /figures/
└── gráficos e imagens usadas no TCC
LICENSE
README.md


## 📊 Dados

Os dados utilizados neste trabalho provêm do banco público de monitoramento da **CETESB**, referentes ao ponto **TIET04200** na bacia do Alto Tietê.

> **Obs.:** Os dados originais **não estão incluídos no repositório** por questões de direitos e tamanho.  
O usuário deve obtê-los diretamente no site da CETESB.

---

## ▶️ Como Executar o Projeto

### 1. Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO



