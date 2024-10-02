# Análise de Sentimentos com Bag of Words e TF-IDF

Este projeto foi desenvolvido como parte de um trabalho acadêmico com o objetivo de realizar **análise de sentimentos** em textos, utilizando técnicas de **Processamento de Linguagem Natural (NLP)**. O foco do projeto está na aplicação de **Bag of Words** e **TF-IDF** em dois modelos de classificação: **Regressão Logística** e **Naive Bayes Multinomial**.

## 🚀 Funcionalidades

- **Pipeline de Regressão Logística**: Usando a técnica **Bag of Words** para converter textos em vetores de contagem de palavras.
- **Pipeline de Naive Bayes Multinomial**: Utilizando **TF-IDF** para ponderar palavras com base na frequência e relevância em todo o corpus de textos.
- **Análise de Sentimentos**: Classificação de textos como **positivos** ou **negativos**.
- **Pré-processamento de Texto**: Limpeza dos textos, remoção de stopwords e tokenização para garantir dados prontos para a modelagem.

## 🛠️ Tecnologias Utilizadas

As principais ferramentas e bibliotecas usadas neste projeto são:

- **Python**: Linguagem de programação principal para o desenvolvimento do projeto.
- **scikit-learn**: Para construção dos pipelines de aprendizado de máquina.
- **NLTK**: Para o pré-processamento de texto (remoção de stopwords e tokenização).
- **Pandas**: Para manipulação e análise dos dados.
- **Jupyter Notebooks**: Para execução e visualização dos experimentos e resultados.

## 📊 Explicação dos Modelos

### Bag of Words (BoW)
A técnica **Bag of Words** transforma o texto em vetores de contagem, sem considerar a ordem das palavras. Cada documento é representado por um vetor, onde cada posição indica a frequência com que uma palavra específica aparece no documento. Esse método é utilizado em um pipeline com **Regressão Logística**, que é um classificador linear eficaz para problemas de classificação binária, como análise de sentimentos.

### TF-IDF (Term Frequency-Inverse Document Frequency)
O **TF-IDF** é uma técnica que ajusta a contagem de palavras com base em sua importância relativa em um corpus. Ele reduz o peso de palavras muito comuns e dá mais importância a termos raros e relevantes. Esta técnica é aplicada em um pipeline com **Naive Bayes Multinomial**, que é um classificador probabilístico amplamente utilizado em problemas de classificação de texto.

## 📝 Como Utilizar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/RodrigoSiliunas/bluesky-vibes-coffe
   ```
2. **Instale as dependências**: Certifique-se de estar em um ambiente virtual Python e execute
   ```bash
   pip install -r requirements.txt
   ```
3. **Execute o projeto**: Abra o Jupyter Notebook ou execute os scripts Python para treinar os modelos e testar a classificação de sentimentos.
   ```bash
   jupyter notebook
   ```
4. **Testar o modelo**: Após o treinamento dos modelos, você pode inserir novas frases para análise de sentimentos, por exemplo:
   ```bash
   is_positive_text(clean_text("Estou muito feliz com este produto!"))
   ```

## 📈 Resultados e Conclusões
* O pipeline de Bag of Words com Regressão Logística apresentou bons resultados para a tarefa de classificação de sentimentos, sendo uma solução eficiente e simples.
* O pipeline de TF-IDF com Naive Bayes Multinomial mostrou-se menos eficiente em textos curtos mas mais robusto ao lidar com palavras muito frequentes, resultando em uma melhor generalização em alguns casos.

## 🤝 Contribuições
Este é um projeto acadêmico, mas contribuições são bem-vindas. Sinta-se à vontade para abrir issues ou enviar pull requests.

## ▶️ Video Explicativo

[![Assista ao vídeo no YouTube](https://img.youtube.com/vi/EXEMPLO/hqdefault.jpg)](https://www.youtube.com/watch?v=7QjMWERwf34)
