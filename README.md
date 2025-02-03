# Chatbot com IA Generativa e Banco de Dados

## Descrição

Este projeto é um chatbot baseado em IA generativa que responde apenas com informações presentes no seu banco de dados. Ele não gera respostas fora dos dados armazenados, garantindo maior precisão e controle sobre as respostas.

## Funcionalidades

- Processamento de linguagem natural (NLP) para entender perguntas do usuário.
- Consulta a um banco de dados para fornecer respostas baseadas apenas nas informações disponíveis.
- Capacidade de armazenar contexto para manter a coerência nas respostas.
- Integração com APIs externas para buscas otimizadas dentro do banco de dados.
- Interface web para interação com os usuários.

## Tecnologias Utilizadas

- **Backend:** Python (Flask)
- **Banco de Dados:** MySQL
- **Processamento de Texto:** Transformers 
- **Integração de IA:** GEMINI
- **Frontend:** HTML, CSS, JavaScript 

## Como Funciona

1. O usuário envia uma pergunta para o chatbot.
2. O chatbot analisa a pergunta e verifica no banco de dados se há uma resposta relevante.
3. Se a informação estiver no banco, o chatbot retorna uma resposta baseada nos dados encontrados.
4. Se não houver informação no banco de dados, o chatbot informa que não pode responder.


