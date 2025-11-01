# 🤖 Chatbot Baseado em Conteúdo de PDFs

Este projeto faz parte do desafio da DIO **"Criando um Chatbot Baseado em Conteúdo de PDFs"**.  
O objetivo foi criar um sistema capaz de responder perguntas com base em documentos enviados pelo usuário, utilizando **IA generativa**, **embeddings** e **busca vetorial**.

---

## 🚀 Visão Geral

O sistema processa os arquivos PDF carregados, converte o texto em embeddings e armazena-os em um índice vetorial.  
Durante a interação, o chatbot localiza os trechos mais relevantes no espaço vetorial e gera respostas coerentes e contextuais.

---

## 🧩 Etapas do Projeto

1. **Carregamento de PDFs:** leitura e extração de texto.  
2. **Criação de embeddings:** conversão do texto em vetores numéricos.  
3. **Indexação vetorial:** armazenamento dos embeddings para busca eficiente.  
4. **Chat interativo:** o usuário faz perguntas, e a IA busca informações relevantes nos PDFs antes de responder.

---

## 🧠 Exemplos de uso

Pergunta: *O que são embeddings?*  
Resposta gerada: *Embeddings são representações numéricas de palavras ou frases que capturam o significado semântico e permitem buscas por similaridade entre textos.*

---

## 💡 Insights e Aprendizados

- Compreendi a importância dos **embeddings** para consultas semânticas.  
- Aprendi como **buscas vetoriais** podem superar a limitação de palavras exatas.  
- O uso de **IA generativa** oferece respostas contextualizadas a partir de informações específicas.  
- O projeto pode ser expandido para áreas como **assistentes acadêmicos**, **análise de contratos** ou **suporte técnico interno**.

---

## 📸 Prints

*(adicione aqui imagens do notebook, console ou da aplicação rodando)*

---

## 📚 Próximos passos

- Adicionar upload direto de PDFs na interface.  
- Implementar cache de embeddings para otimizar buscas.  
- Integrar com Azure AI Foundry para orquestração de fluxos e métricas automáticas.

---

**Autor:** rafael-fj
**Desafio:** DIO — Criando um Chatbot Baseado em Conteúdo de PDFs
