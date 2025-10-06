💡 Classificação de Sentimentos com Processamento de Linguagem Natural (PLN)
🚀 Este é um projeto simples e funcional de Processamento de Linguagem Natural (PLN), desenvolvido em Python, que permite classificar textos como positivos ou negativos com base em seu conteúdo.

✅ Objetivo: Demonstrar o uso de técnicas básicas de PLN e Machine Learning para analisar sentimentos em textos.

📝 Descrição do Projeto
Este projeto utiliza um pequeno conjunto de frases pré-classificadas para treinar um modelo de Machine Learning que realiza análise de sentimentos. A aplicação é ideal para iniciantes que desejam compreender conceitos fundamentais de PLN, como:

Limpeza e pré-processamento de textos;
Vetorização de dados textuais (Bag of Words);
Criação e treinamento de um modelo de classificação usando o algoritmo Naive Bayes Multinomial.
Exemplo de entrada para o modelo:

"Achei o produto incrível, vou recomendar!"

Saída do modelo:

Positivo 🎉

🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido com as seguintes ferramentas e bibliotecas:

Python 🐍
www.nltk.org
 – Para tarefas de processamento de linguagem natural, como remoção de stopwords.

scikit-learn.org
 – Para vetorização de textos, criação do modelo de Machine Learning e avaliação.
string – Para manipulação básica de textos.

⚙️ Como Funciona

1️⃣ Etapas do processo:
Pré-Processamento dos Textos
Remoção de pontuações e stopwords (palavras irrelevantes como “o”, “de”, “é”).
Conversão de textos para minúsculas.
Transformação dos Textos (Vetorização)
Utilizamos a técnica Bag of Words, que converte palavras em vetores de frequência, para alimentar o modelo de Machine Learning.
Treinamento e Teste do Modelo
Algoritmo utilizado: Multinomial Naive Bayes – Modelo clássico para PLN.
Avaliação com métricas de precisão para medir a eficácia da classificação.
Classificação de Novos Textos
O modelo final é utilizado para prever o sentimento de frases novas.
🚀 Como Executar o Projeto
📦 Pré-requisitos
Python 3.7+ instalado na sua máquina.
As bibliotecas necessárias podem ser instaladas com o comando abaixo:

bash

pip install -r requirements.txt
🏃‍♂️ Passo a passo para rodar:
Clone este repositório:
bash


git clone https://github.com/seu-usuario/pln-sentiment-analysis.git
Navegue até o diretório do projeto:
bash

cd pln-sentiment-analysis
Execute o script principal:
bash


python main.py
Resultado:
A saída exibirá a precisão do modelo.
Você poderá testar o modelo inserindo novas frases!

📜 Licença
Este projeto é distribuído sob a licença MIT. Veja o arquivo LICENSE para mais informações.

💬 Contato
📧 Caso tenha dúvidas ou sugestões, entre em contato pelo e-mail: seuemail@dominio.com.

🎉 Divirta-se aprendendo PLN!
