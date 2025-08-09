# Treinamento de Modelo com CNN e Espectrogramas de Mel

## 📄 Sobre o Projeto

Este projeto demonstra o processo completo de treinamento de um modelo de *Deep Learning* para classificação de áudio. A abordagem utiliza **Redes Neurais Convolucionais (CNNs)**, que são alimentadas com **Espectrogramas de Mel**, uma representação visual do espectro de um sinal de áudio.

O objetivo é .

### ✨ Principais Funcionalidades

* **Pré-processamento de Áudio**: Conversão de arquivos de áudio para Espectrogramas de Mel.
* **Arquitetura do Modelo**: Implementação de uma Rede Neural Convolucional.
* **Treinamento e Validação**: Script para treinar o modelo com os dados de treino e validá-lo.
* **Avaliação de Performance**: Cálculo de métricas de avaliação como acurácia e perda (loss).

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido no ambiente **Google Colab**, utilizando as seguintes tecnologias e bibliotecas:

* **Python**
* **TensorFlow / Keras**: Para a criação e treinamento do modelo de Deep Learning.
* **Librosa**: Para análise e extração de características de áudio (geração dos Espectrogramas de Mel).
* **NumPy**: Para manipulação eficiente de arrays multidimensionais.
* **Matplotlib / Seaborn**: Para visualização de dados e resultados durante a análise.
* **Scikit-learn**: Para a divisão de dados e avaliação de métricas.
* **Pandas**: Para manipulação e análise de metadados.
* **Google Drive API**: Para conectar e acessar os arquivos do dataset no ambiente Colab.

---

## 🚀 Como Executar o Projeto

### Opção 1: Google Colab (Recomendado)

1.  Acesse o notebook: [Link para o Google Colab](https://colab.research.google.com/drive/152GGQgPbagptKeMwc769B6uuTivFf2js)
2.  Conecte seu Google Drive para dar acesso ao dataset.
3.  Execute as células do notebook em sequência para treinar e avaliar o modelo.

### Opção 2: Ambiente Local

Caso queira executar em sua máquina, será necessário adaptar o código para um ambiente local.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/KaremLeticia/Treinamento_de_Modelo_com_CNN_e_Espectrogramas_de_Mel.git](https://github.com/KaremLeticia/Treinamento_de_Modelo_com_CNN_e_Espectrogramas_de_Mel.git)
    cd Treinamento_de_Modelo_com_CNN_e_Espectrogramas_de_Mel
    ```

2.  **Crie e ative um ambiente virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install tensorflow librosa numpy matplotlib seaborn scikit-learn pandas jupyter
    ```
---

## 📈 Resultados

O modelo alcançou as seguintes métricas de performance após o treinamento:

* **Acurácia de Treino**: * **Acurácia de Validação**: * **Perda (Loss) de Treino**: * **Perda (Loss) de Validação**: ---

## ✍️ Autor

* **Karem Leticia** - [GitHub](https://github.com/KaremLeticia)

---

## 📄 Licença

Este projeto está sob a licença MIT.
