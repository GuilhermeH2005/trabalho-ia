# 🧠 Trabalho de Inteligência Artificial

**Da ELIZA aos Transformers**

---

## 📌 Descrição

Este projeto tem como objetivo demonstrar a evolução do Processamento de Linguagem Natural (NLP), desde sistemas simbólicos baseados em regras até modelos estatísticos e vetoriais, chegando aos modelos modernos baseados em Deep Learning.

O trabalho foi dividido em etapas que representam diferentes momentos históricos da IA, conforme proposto na atividade.

---

## 🚀 Fases do Projeto

---

### 🤖 Fase 1: Chatbot estilo ELIZA (Era Simbólica)

#### 🔧 Funcionamento

* Implementação inspirada no ELIZA (1966)
* Uso de **Expressões Regulares (Regex)**
* Identificação de palavras-chave
* Respostas baseadas em padrões pré-definidos
* Simulação de diálogo simples

#### 📊 Resultados

* Interações simples com o usuário
* Respostas coerentes dentro dos padrões definidos
* Simulação básica de conversa

#### ⚠️ Limitações

* Não compreende o significado real das frases
* Baseado apenas em padrões e palavras-chave
* Respostas limitadas e previsíveis
* Não possui memória de contexto

---

### 🔗 Fase 2: Predição com N-grams (Revolução Estatística)

#### 🔧 Funcionamento

* Modelo baseado em **bigramas (N=2)**
* Predição da próxima palavra com base na anterior
* Uso de frequência e probabilidade
* Geração automática de frases a partir de um corpus

> Segue o princípio das Cadeias de Markov, onde o próximo estado depende apenas do estado atual.

#### 📊 Resultados

* Geração automática de frases
* Capacidade de prever palavras com base em frequência
* Demonstração de modelo estatístico simples

#### ⚠️ Limitações

* Contexto extremamente limitado
* Pode gerar frases incoerentes
* Não entende significado semântico
* Dependência total do corpus

---

### 🧮 Fase 3: Word2Vec (Vetores e Contexto)

#### 🔧 Funcionamento

* Uso da biblioteca **gensim**
* Representação de palavras como vetores numéricos
* Cálculo de similaridade semântica
* Operações vetoriais (ex: `gato - leite + carne`)

#### 📊 Resultados

* Identificação de palavras semelhantes
* Associação de contexto entre termos
* Demonstração de relações semânticas

#### ⚠️ Limitações

* Corpus pequeno limita os resultados
* Similaridade nem sempre precisa
* Sensível à qualidade dos dados

---

### 🤖 Fase 4: Transformers e Atenção (Deep Learning)

#### 🔧 Funcionamento

* Uso da biblioteca **transformers**
* Modelo pré-treinado (GPT-2 em português)
* Geração de texto baseada em entrada do usuário
* Utilização do mecanismo de **atenção (attention)**

#### 🧠 Conceito de Atenção

O mecanismo de atenção permite que o modelo analise toda a frase ao mesmo tempo, identificando quais palavras são mais importantes para o contexto.

#### 📊 Resultados

* Geração de textos mais naturais e coerentes
* Melhor compreensão de contexto
* Respostas mais próximas da linguagem humana

#### ⚠️ Limitações

* Alto custo computacional
* Pode gerar informações incorretas
* Depende de grandes volumes de dados
* Nem sempre garante respostas totalmente precisas

---

## 🛠️ Tecnologias Utilizadas

* Python
* Biblioteca **gensim** (Word2Vec)
* Biblioteca **transformers** (Deep Learning)
* Expressões Regulares (Regex)
* Google Colab / Jupyter Notebook

---

## ▶️ Como Executar

1. Instale as dependências:

```bash
pip install gensim transformers torch
```

2. Execute os arquivos:

* `eliza.py`
* `ngrams.py`
* `word2vec.py`
* `transformers.py`

---

## 📌 Conclusão

Este trabalho demonstra a evolução das técnicas de NLP ao longo do tempo:

* **ELIZA** → abordagem simbólica baseada em regras
* **N-grams** → abordagem estatística baseada em probabilidade
* **Word2Vec** → representação vetorial e semântica
* **Transformers** → modelos modernos baseados em Deep Learning e atenção

Cada abordagem apresenta vantagens e limitações, mostrando como a Inteligência Artificial evoluiu para modelos cada vez mais sofisticados e capazes de compreender linguagem natural.

