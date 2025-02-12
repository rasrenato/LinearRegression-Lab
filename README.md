# 🌊 Laboratório de Regressão Linear Interativa / Interactive Linear Regression Lab

Este repositório contém os exercícios do laboratório opcional do curso **"Aprendizado de Máquina Supervisionado: Regressão e Classificação"**. O laboratório explora a implementação de **Regressão Linear Univariada e Multivariada** e a criação de **visualizações interativas**.

This repository contains the exercises from the optional lab of the **"Supervised Machine Learning: Regression and Classification"** course. The lab explores the implementation of **Univariate and Multivariate Linear Regression** and the creation of **interactive visualizations**.

---

## 📂 Estrutura do Repositório / Repository Structure

```plaintext
LinearRegression-Lab/
│── C1_W1_Lab02_Model_Representation_Soln.ipynb  # Representação do modelo / Model representation
│── C1_W1_Lab03_Cost_function_Soln.ipynb         # Visualização da função de custo / Cost function visualization
│── C1_W1_Lab04_Gradient_Descent_Soln.ipynb      # Algoritmo do gradiente descendente / Gradient descent algorithm
│── C1_W2_Lab01_Python_Numpy_Vectorization_Soln.ipynb  # Vetorização e operações NumPy / NumPy Vectorization
│── C1_W2_Lab02_Multiple_Variable_Soln.ipynb  # Regressão linear com múltiplas variáveis / Multiple Variable Regression
│── C1_W2_Lab03_Feature_Scaling_and_Learning_Rate_Soln.ipynb  # Escalonamento de features e taxa de aprendizado / Feature Scaling and Learning Rate
│── C1_W2_Lab04_FeatEng_PolyReg_Soln.ipynb  # Engenharia de features e regressão polinomial / Feature Engineering and Polynomial Regression
│── C1_W2_Lab05_Sklearn_GD_Soln.ipynb  # Gradiente descendente com Scikit-Learn / Gradient Descent with Scikit-Learn
│── requirements.txt                             # Dependências do projeto / Project dependencies
│── README.md                                    # Informações do projeto / Project information
```

---

## 📌 Como Usar / How to Use

1. **Clone este repositório**

   ```sh
   git clone https://github.com/rasrenato/LinearRegression-Lab.git
   cd LinearRegression-Lab
   ```

2. **Instale as dependências**

   ```sh
   pip install -r requirements.txt
   ```

3. **Execute os notebooks no Jupyter**

   ```sh
   jupyter notebook
   ```

   Abra os arquivos `.ipynb` no Jupyter Notebook ou JupyterLab.   Open the `.ipynb` files in Jupyter Notebook or JupyterLab.

---

## 📊 Descrição dos Notebooks / Notebook Descriptions

| Arquivo                                                              | Descrição                                                                                                        |
| -------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **C1\_W1\_Lab02\_Model\_Representation\_Soln.ipynb**                 | Implementação da representação do modelo de regressão linear univariada.                                         |
| **C1\_W1\_Lab03\_Cost\_function\_Soln.ipynb**                        | Visualização da função de custo convexa para regressão linear (formato "soup bowl").                             |
| **C1\_W1\_Lab04\_Gradient\_Descent\_Soln.ipynb**                     | Implementação do algoritmo do gradiente descendente para otimização da regressão linear.                         |
| **C1\_W2\_Lab01\_Python\_Numpy\_Vectorization\_Soln.ipynb**          | Exercícios sobre vetorização e operações NumPy para otimização computacional.                                    |
| **C1\_W2\_Lab02\_Multiple\_Variable_Soln.ipynb**                    | Implementação da regressão linear com múltiplas variáveis, incluindo gráficos de custo e vetorização com np.dot. |
| **C1\_W2\_Lab03\_Feature\_Scaling\_and\_Learning\_Rate\_Soln.ipynb** | Implementação do escalonamento de features e impacto da taxa de aprendizado na convergência.                     |
| **C1\_W2\_Lab04_FeatEng_PolyReg_Soln.ipynb**                         | Implementação de engenharia de features e regressão polinomial.                                                  |
| **C1\_W2\_Lab05_Sklearn_GD_Soln.ipynb**                              | Aplicação do gradiente descendente utilizando Scikit-Learn.                                                      |

---

## 🔍 Exemplo de Visualização / Example Visualization

## 📜 Exercício de Prova - Regressão Linear

Este repositório agora inclui o exercício de prova da regressão linear, que abrange:
- Implementação da função de custo `compute_cost()`
- Cálculo dos gradientes `compute_gradient()`
- Aplicação do gradiente descendente `gradient_descent()`
- Previsão de lucro para populações de 35.000 e 70.000 habitantes

📌 **Arquivo:** `C1_W2_Linear_Regression.ipynb`


Aqui está um exemplo de visualização gerado pelos notebooks deste laboratório:



Se desejar adicionar mais exemplos, inclua imagens que demonstrem a evolução do custo ou os efeitos do escalonamento de features. (Aqui você pode adicionar uma imagem mostrando gráficos gerados pelo notebook para ilustrar os resultados.)

---

## 👨‍💻 Autor / Author

[Renato Abreu Simões](https://github.com/rasrenato)🔗 [LinkedIn](https://www.linkedin.com/in/renato-abreu/)

---

## 📝 Licença / License

Este projeto está licenciado sob a **MIT License**.This project is licensed under the **MIT License**.
