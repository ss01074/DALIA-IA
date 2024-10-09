# DALIA - Chatbot de Análise de Erros

DALIA é um chatbot de Inteligência Artificial (IA) projetado para auxiliar na análise e compreensão de erros em aplicações.  DALIA utiliza uma base de conhecimento de erros, combinada com um modelo de linguagem grande (LLM), para fornecer informações contextuais, identificar possíveis causas raiz e sugerir soluções para problemas.

## Funcionalidades (Planejadas)

* **Consulta sobre erros:** Responda a perguntas sobre erros específicos, fornecendo explicações, causas e possíveis soluções.
* **Análise contextual:** Considere o contexto da aplicação e do erro para fornecer respostas mais relevantes.
* **Sugestões de soluções:** Ofereça sugestões de soluções e micro tarefas para auxiliar na resolução de problemas.
* **Integração com ADAL-IA (futuro):**  Integração com o projeto ADAL-IA para acesso direto à base de conhecimento de erros.
* **Adaptação à linguagem do usuário:**  Adapte-se à linguagem e ao nível técnico do usuário para fornecer respostas mais claras.
* **Interface conversacional:** Interface amigável e intuitiva para interação com o chatbot.


## Tecnologias

* Python
* Rasa (framework de chatbot) - ou similar
* Modelo de Linguagem Grande (LLM) - ex: GPT, BLOOM
* SpaCy/NLTK (Processamento de Linguagem Natural)
* Banco de dados (SQLite, PostgreSQL, ou similar)

## Instalação

1. Clone o repositório: `git clone <repositorio_dalia>`
2. Navegue até a pasta: `cd dalia`
3. Crie um ambiente virtual: `python3 -m venv .venv`
4. Ative o ambiente: `source .venv/bin/activate` (Linux/macOS) ou `.venv\Scripts\activate` (Windows)
5. Instale as dependências: `pip install -r requirements.txt`

## Uso

(Descreva aqui como usar o chatbot DALIA, incluindo comandos e exemplos.)

## Executando os Testes
```bash
pytest

Contribuição
Contribuições são bem-vindas! Veja o arquivo CONTRIBUTING.md para mais detalhes.

Licença
MIT

Contato
Samuel Pedroso dos Santos - sps04028701074@outlook.com

Estrutura do Projeto
plaintext
Copy
dalia/
├── main.py                # Arquivo principal
├── rasa/                  # Configuração do Rasa (se aplicável)
│   ├── config.yml        # ...
│   ├── domain.yml        # ...
│   ├── nlu.yml          # ...
│   ├── stories.yml       # ...
│   ├── actions.py       # ...
│   └── models/           # ...
├── utils/                  # Funções utilitárias
│   ├── database.py       # Interação com o banco de dados
│   └── api_calls.py      # Chamadas de API
├── data/                   # Dados e base de conhecimento
│   └── knowledge_base.json # Base de conhecimento
├── tests/                  # Testes unitários
├── config.py               # Arquivo de configuração
├── pyproject.toml          # Configurações do projeto
├── requirements.txt      # Dependências
├── LICENSE               # Licença
└── CONTRIBUTING.md       # Guia de contribuição