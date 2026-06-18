# 🤖 HR Buddy - Assistente de RH com n8n

Projeto de automação desenvolvido utilizando n8n, inteligência artificial e integração com banco de dados.

## 📌 Sobre o projeto

O HR Buddy é um assistente virtual de RH que responde dúvidas dos funcionários utilizando um agente de IA conectado a uma base de conhecimento e banco de dados.

O projeto utiliza um fluxo automatizado onde o usuário envia uma mensagem pelo Telegram, o agente de IA interpreta a solicitação e busca informações em fontes conectadas para gerar uma resposta.

## 🚀 Funcionalidades

- Atendimento via Telegram
- Agente de Inteligência Artificial
- Memória de conversa
- Busca de informações em Vector Store
- Consulta de funcionários via MySQL
- Respostas baseadas em políticas de RH
- Integração com ferramentas externas através do n8n

## 🛠️ Tecnologias utilizadas

- n8n
- Cohere AI
- MySQL
- Telegram Bot
- Vector Store
- LangChain

## 🔄 Fluxo da automação

Usuário
   ↓
Telegram
   ↓
AI Agent (n8n)
   ↓
Vector Store / MySQL
   ↓
Resposta ao usuário


## 📂 Estrutura do projeto

📂 Estrutura do projeto

n8n-hr-buddy/

├── workflows/
│   └── producao-imersao.json
│
├── README.md
│
└── .gitignore

📥 Como importar no n8n

Abrir o n8n
Acessar a opção de importar workflow
Selecionar o arquivo:
workflows/producao-imersao.json
Configurar as credenciais necessárias:
Telegram
MySQL
Cohere AI

🔐 Segurança

As credenciais e informações sensíveis não são armazenadas neste repositório.
As conexões devem ser configuradas diretamente no ambiente n8n.


📚 Observação

Este projeto foi desenvolvido como projeto de estudo e demonstração de automação com inteligência artificial utilizando n8n.
O objetivo é demonstrar integração entre IA, banco de dados e automações.
