# 🧠 Trabalho de Inteligência Artificial

**Da ELIZA aos Transformers**

---

## 📌 Descrição

Este projeto tem como objetivo demonstrar a evolução do Processamento de Linguagem Natural (NLP), desde sistemas simbólicos baseados em regras até modelos estatísticos e vetoriais.

O trabalho foi dividido em etapas que representam diferentes momentos históricos da IA, conforme proposto na atividade.

---

## 🚀 Funcionalidades

O projeto está dividido em três fases implementadas:

---

### 🤖 Fase 1: Chatbot estilo ELIZA (Era Simbólica)

* Implementação inspirada no ELIZA (1966)
* Uso de **Expressões Regulares (Regex)**
* Identificação de palavras-chave
* Respostas baseadas em padrões pré-definidos
* Simulação de diálogo simples

---

### 🔗 Fase 2: Predição com N-grams (Revolução Estatística)

* Implementação de modelo baseado em **bigramas (N=2)**
* Predição da próxima palavra com base na anterior
* Modelo baseado em **frequência e probabilidade**
* Geração automática de frases a partir de um corpus

> Este modelo segue o princípio das Cadeias de Markov, onde o próximo estado depende apenas do estado atual.

---

### 🧮 Fase 3: Word2Vec (Vetores e Contexto)

* Uso da biblioteca **gensim**
* Representação de palavras como vetores numéricos
* Cálculo de **similaridade semântica (cosseno)**
* Identificação de palavras mais próximas
* Aplicação de **operações vetoriais**, como:

  * `gato - leite + carne`

---

## 📊 Resultados

* O modelo identificou relações entre palavras como "gato" e "cachorro"
* Foi possível observar associações contextuais (ex: "cachorro" → "carne")
* As operações vetoriais demonstraram o funcionamento dos embeddings
* O modelo de N-grams gerou frases baseadas em probabilidades

> Devido ao corpus reduzido, os resultados não são totalmente precisos, o que é esperado em modelos simples.

---

## ⚠️ Limitações

### 🤖 Chatbot estilo ELIZA

* Não compreende o significado real das frases
* Baseado apenas em padrões e palavras-chave
* Respostas limitadas e previsíveis
* Não possui memória de contexto

---

### 🔗 N-grams

* Contexto extremamente limitado (apenas 1 ou poucas palavras anteriores)
* Pode gerar frases sem sentido ou incoerentes
* Não entende significado semântico
* Depende totalmente da frequência no corpus

---

### 🧮 Word2Vec

* Resultados limitados devido ao corpus pequeno
* Similaridade nem sempre precisa
* Operações vetoriais podem gerar resultados inesperados
* Sensível à qualidade dos dados

---

## 🛠️ Tecnologias Utilizadas

* Python
* Biblioteca **gensim** (Word2Vec)
* Expressões Regulares (Regex)
* Google Colab / Jupyter Notebook

---

## ▶️ Como Executar

1. Instale as dependências:

   ```bash
   pip install gensim
   ```

2. Execute os scripts:

   * Chatbot ELIZA
   * Gerador de texto com N-grams
   * Modelo Word2Vec



---

## 📌 Considerações Finais

Este trabalho demonstra a evolução das abordagens em NLP:

* Sistemas simbólicos (ELIZA)
* Modelos estatísticos (N-grams)
* Representações vetoriais (Word2Vec)

Cada abordagem apresenta vantagens e limitações, evidenciando como a Inteligência Artificial evoluiu ao longo do tempo.

---
