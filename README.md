# Aplicação Multi Agentes para uma concessionária de veículos

## Para rodar a aplicação:

- Necessário criar o arquivo .env e inserir no parâmentro 'OPENAI_API_KEY' a chave da API. No caso está sendo usado o da OPENIA, caso utilize outro fornecedor de modelo o código também necessita de adaptação.
  
- Importante criar um ambiente virtual e instalar o requirements.txt onde está listado as bibliotecas necessárias e suas respectivas versões.

### Criação de ambiente virtual:

- python3 -m venv venv
    - venv é o nome convencionado, porém pode ser qualquer outro nome para identificar o ambiente virtual que está sendo criado.
- source venv/bin/activate
- deactivate
  - para desativar o ambiente virtual.

### Instalação das bibliotecas

- pip install -r requirements.txt

## Executando a aplicação

- python3 -m streamlit run streamlit_agents/chat_multi_agent.py 

