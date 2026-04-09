# 🤖 Assistente RAG de Políticas Internas (RH)

Aplicação de Inteligência Artificial baseada em **RAG (Retrieval-Augmented Generation)** para responder perguntas sobre políticas internas de RH a partir de documentos PDF.

---

## 📌 Sobre o projeto

Este projeto utiliza técnicas modernas de IA para criar um assistente capaz de responder perguntas com base em documentos internos da empresa.

O sistema:

* Lê um arquivo PDF com políticas de RH
* Divide o conteúdo em blocos menores
* Converte os textos em embeddings
* Armazena em um banco vetorial (FAISS)
* Recupera os trechos mais relevantes
* Gera respostas usando um modelo de linguagem

---

## 🧠 O que é RAG?

RAG (Retrieval-Augmented Generation) é uma técnica que combina:

* 🔎 Busca de informações (retrieval)
* 🤖 Geração de texto com IA (LLM)

Isso permite respostas mais precisas e baseadas em dados reais.

---

## 🛠️ Tecnologias utilizadas

* Python
* Streamlit (interface web)
* LangChain (orquestração de IA)
* FAISS (banco vetorial)
* OpenAI (embeddings + modelo de linguagem)
* PyPDF (leitura de documentos)

---

## ⚙️ Funcionalidades

✅ Leitura de PDF com políticas internas
✅ Divisão de texto em chunks
✅ Geração de embeddings
✅ Busca semântica com FAISS
✅ Geração de respostas com IA
✅ Interface interativa com Streamlit

---

## 📁 Estrutura do projeto

```id="v2n8p1"
rag-rh-assistente/
│
├── app.py
├── politica_rh.pdf
├── requirements.txt
├── .env
└── README.md
```

---

## 🔐 Configuração da API

Crie um arquivo `.env` na raiz do projeto:

```id="k6rm7h"
OPENAI_API_KEY=sua_chave_aqui
```

---

## 📦 Instalação

Clone o repositório:

```id="5ss3bt"
git clone https://github.com/SEU_USUARIO/rag-rh-assistente.git
```

Instale as dependências:

```id="fxc4bl"
pip install -r requirements.txt
```

---

## ▶️ Como executar

```id="u6v4s2"
streamlit run app.py
```

---

## 💬 Exemplo de uso

Pergunta:

> "Qual é a política de férias da empresa?"

Resposta:

> O assistente busca no documento e responde com base no conteúdo encontrado.

---

## ⚠️ Observações

* O modelo responde apenas com base no conteúdo do PDF
* Caso a informação não exista, ele informa que não sabe
* Necessário conexão com internet para uso da API

---

## 🚀 Melhorias futuras

* Upload de múltiplos PDFs
* Interface mais avançada
* Deploy em nuvem
* Histórico de conversas
* Autenticação de usuários

---

## 🎯 Objetivo

Demonstrar conhecimentos em:

* Inteligência Artificial aplicada
* RAG (Retrieval-Augmented Generation)
* LangChain e LLMs
* Engenharia de dados para IA

---

## 👨‍💻 Autor

Desenvolvido por **Wander Farias** 🚀
