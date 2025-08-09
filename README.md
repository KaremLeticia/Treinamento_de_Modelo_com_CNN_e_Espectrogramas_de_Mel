# Treinamento de Modelo com CNN e Espectrogramas de Mel

![Banner](httpsd://user-images.githubusercontent.com/109232048/202933756-6a864731-1579-4679-b148-c923d536777c.png)


## 📄 Sobre o Projeto

Este projeto demonstra o processo completo de treinamento de um modelo de *Deep Learning* para classificação de áudio. A abordagem utiliza **Redes Neurais Convolucionais (CNNs)**, que são alimentadas com **Espectrogramas de Mel**, uma representação visual do espectro de um sinal de áudio.

O objetivo é .

### ✨ Principais Funcionalidades

* **Pré-processamento de Áudio**: Conversão de arquivos de áudio (`.wav`, `.mp3`, etc.) para Espectrogramas de Mel.
* **Arquitetura do Modelo**: Implementação de uma Rede Neural Convolucional utilizando a biblioteca Keras/TensorFlow.
* **Treinamento e Validação**: Script para treinar o modelo com os dados de treino e validá-lo.
* **Avaliação de Performance**: Métricas de avaliação como acurácia, precisão, recall e matriz de confusão.
* **Visualização de Dados**: Gráficos para análise dos espectrogramas e dos resultados do modelo.

---

## 🛠️ Tecnologias Utilizadas

As principais tecnologias e bibliotecas utilizadas no desenvolvimento do projeto foram:

* **Python 3.x**
* **TensorFlow / Keras**: Para a criação e treinamento do modelo de Deep Learning.
* **Librosa**: Para análise e extração de características de áudio (geração dos Espectrogramas de Mel).
* **NumPy**: Para manipulação eficiente de arrays multidimensionais.
* **Matplotlib / Seaborn**: Para visualização de dados e resultados.
* **Scikit-learn**: Para a divisão de dados e avaliação de métricas (matriz de confusão, classification report).
* **Jupyter Notebook**: Para prototipagem e análise exploratória.

---

## 📂 Estrutura do Projeto

O repositório está organizado da seguinte forma:
├── data/                  # Pasta para armazenar o dataset de áudio
│   ├── class_1/
│   └── class_2/
├── notebooks/             # Contém os notebooks de exploração e prototipagem
│   └── exploracao_e_modelo.ipynb
├── src/                   # Contém o código fonte modularizado
│   ├── preprocess.py      # Script para pré-processar os dados de áudio
│   ├── model.py           # Arquitetura do modelo CNN
│   └── train.py           # Script principal para treinamento
├── requirements.txt       # Lista de dependências do projeto
└── README.md              # Este arquivo

---

## 🚀 Como Executar o Projeto

Siga os passos abaixo para configurar e executar o projeto em seu ambiente local.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:
* [Git](https://git-scm.com)
* [Python 3.8+](https://www.python.org/downloads/)
* (Opcional, mas recomendado) Um gerenciador de ambientes como [venv](https://docs.python.org/3/library/venv.html) ou [Conda](https://docs.conda.io/en/latest/).

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/KaremLeticia/Treinamento_de_Modelo_com_CNN_e_Espectrogramas_de_Mel.git](https://github.com/KaremLeticia/Treinamento_de_Modelo_com_CNN_e_Espectrogramas_de_Mel.git)
    cd Treinamento_de_Modelo_com_CNN_e_Espectrogramas_de_Mel
    ```

2.  **(Recomendado) Crie e ative um ambiente virtual:**
    ```bash
    # Usando venv
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    Crie um arquivo `requirements.txt` no seu repositório (se ainda não tiver um) e instale as bibliotecas necessárias.
    ```bash
    pip install -r requirements.txt
    ```
    *Exemplo de `requirements.txt`:*
    ```txt
    tensorflow
    librosa
    numpy
    matplotlib
    seaborn
    scikit-learn
    jupyter
    ```

### Uso

1.  **Prepare o Dataset**:
    Faça o download do dataset e coloque os arquivos de áudio na pasta `data/`.
    2.  **Pré-processamento dos Dados**:
    Execute o script para converter os áudios em Espectrogramas de Mel.
    ```bash
    python src/preprocess.py
    ```

3.  **Treinamento do Modelo**:
    Para iniciar o treinamento da rede neural, execute:
    ```bash
    python src/train.py
    ```

---

## 📈 Resultados

O modelo alcançou os seguintes resultados após o treinamento:

* **Acurácia de Treino**: * **Acurácia de Validação**: **Matriz de Confusão:**

![Matriz de Confusão](caminho/para/sua/imagem_matriz.png)

**Curvas de Aprendizagem (Acurácia e Perda):**

![Curvas de Aprendizagem](caminho/para/sua/imagem_curvas.png)

---

## ✍️ Autor

* **Karem Leticia** - [GitHub](https://github.com/KaremLeticia)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
