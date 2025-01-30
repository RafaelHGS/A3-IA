# **Análise e Predição de Preços de Carros com Random Forest e KNN**  

📌 **Projeto da disciplina de Inteligência Artificial - Universidade Anhembi Morumbi**  
🎯 **Objetivo**: Refinar a análise de preços de veículos utilizando aprendizado de máquina, comparando os algoritmos **Random Forest** e **K-Nearest Neighbors (KNN)**.  

## 🚗 **Sobre o Projeto**  

Este projeto aprimora um estudo de predição de preços de carros, baseado na base de dados ["Car Features and MSRP"](https://www.kaggle.com/datasets/CooperUnion/cardataset). Ele é uma versão revisada do código original disponível no Kaggle ([referência](https://www.kaggle.com/code/waleedfaheem/car-price-analysis-and-prediction-r2-0-95)), trazendo melhorias no pré-processamento e uma divisão da base de dados em duas categorias:  
✅ **Carros populares**  
✅ **Carros de luxo/performance**  

Além disso, comparamos a eficácia do **Random Forest Regressor (RFR)** com o algoritmo **K-Nearest Neighbors Regressor (KNN)**, analisando a precisão de cada modelo.  

---

## 🔎 **Etapas do Projeto**  

### 1️⃣ **Tratamento da Base de Dados**  
- Remoção de valores nulos e duplicados  
- Separação da base em **carros populares** e **carros de luxo/performance**  
- Análise de distribuição dos preços  

### 2️⃣ **Modelagem e Treinamento**  
- Aplicação do **Random Forest Regressor** e **KNN Regressor** para prever preços  
- Comparação das métricas de desempenho  

### 3️⃣ **Resultados e Comparação dos Algoritmos**  
- O **Random Forest** apresentou melhor desempenho global, especialmente em bases densas  
- O **KNN** teve bons resultados, mas sofreu mais com a complexidade dos dados  

---

## 📊 **Principais Descobertas**  

🔹 **Distribuição dos Preços**  
- Carros populares: Maioria com preços até **50 mil dólares**  
- Carros de luxo/performance: Concentração entre **20 mil e 65 mil dólares**, com alguns modelos acima de **100 mil dólares**  

🔹 **Comparação de Algoritmos (Métrica R² Score)**  

| Algoritmo | Carros Populares | Carros de Luxo/Performance |  
|-----------|----------------|---------------------------|  
| **Random Forest** | **0.85** | **0.96** |  
| **KNN** | **0.82** | **0.90** |  

- **Random Forest se destacou**, especialmente em bases mais densas  
- **KNN teve desempenho satisfatório**, mas perde precisão com grandes quantidades de dados  

---

## 📂 **Como Executar o Projeto**  

1️⃣ **Clone o repositório**  
```bash
git clone <URL_DO_REPOSITÓRIO>
cd <NOME_DO_REPOSITÓRIO>
```

2️⃣ **Instale as dependências**  
```bash
pip install -r requirements.txt
```

3️⃣ **Execute o Jupyter Notebook**  
```bash
jupyter notebook
```
E abra o arquivo `RFRvsKNN.ipynb`.  

---

## 🎓 **Autores**  

- **Daniel Ikeda Kuniyoshi**  
- **Diego Fernandes Martinez**  
- **Nayane Pereira Mazaro**  
- **Pedro Shiraishi de Almeida**  
- **Rafael Henrique Gonçalves Soares**  
- **Vinicius Alves Vieira**  

📌 **Universidade Anhembi Morumbi - 2024**  

---

## **📌 Considerações Finais**  

Esse estudo reforça a importância da escolha do algoritmo adequado para cada tipo de base de dados. O **Random Forest** demonstrou maior precisão, especialmente para bases mais densas, enquanto o **KNN** apresentou bons resultados, mas perdeu desempenho conforme os dados aumentavam.  

🚀 **Se você deseja explorar mais sobre esse projeto ou contribuir, fique à vontade para abrir uma issue ou um pull request!**  
