## Sobre este repositório

Trabalho acadêmico de pós-graduação FIAP, sem fins ou utilidades comerciais e projetado para experimento e estudo apenas.

## Créditos/Licenças

Fonte dos dados utilizados para o experimento: https://github.com/pubmedqa/pubmedqa

## Versão do Python
Python 3.14.3

## Instruções para execução do projeto
Crie um ambiente virtual para execução do código:

```python -m venv .venv```

Inicialize o ambiente virtual:

```source .venv/bin/activate```

E então instalar as dependências através do arquivo requirements.txt:

```pip install -r requirements.txt```

As dependências do Jupyter Notebooks estão contidas no arquivo `requirements.txt`, portanto para editar e depurar o projeto basta rodar o executável a partir do diretório do projeto:

```jupyter notebook```

## Variáveis de ambiente necessárias

```
OPENAI_API_KEY="<your-openai-api-key>"
LANGSMITH_TRACING=true
LANGSMITH_API_KEY="<your-langsmith-api-key>"
```

## Observação importante
Para rodar localmente o arquivo `AutomatedFlow.ipynb` é preciso alterar o modelo, pois a LLM gerada através do fine tuning não é publica.
