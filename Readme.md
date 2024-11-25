# Desafio Murabei

**Nome:** Akyla de Aquino Pinto  
**Email:** akylaaquino@hotmail.com

## Organização do Projeto

O projeto está organizado em 2 scripts e 1 pasta de dados:

- **main.ipynb:** Responsável por modelar os dados e preparar para passar para o modelo de IA.
- **model.ipynb:** Responsável por treinar o modelo e responder as questões do desafio.
- **data:** Pasta de organização dos dados, dividida em bronze, silver e gold.

### Dados de Análise

Os dados de análise encontram-se na pasta `data`, divididos em 3 partes:

- **bronze:** Dados brutos, sem tratamento.
- **silver:** Dados tratados, mas com alguns ajustes e análises a realizar.
- **gold:** Dados tratados e ajustados para o modelo de IA.

## Instalação das Dependências

Para instalar as dependências, utilize o comando:

```bash
pip install -r requirements.txt
```

## Dificuldades do Projeto

As dificuldades enfrentadas foram:

1. Analisar com cuidado os dados a serem unidos, como na parte de cada escola ter seus estudantes.
2. Não consegui entender ao certo por que o modelo treinado não tem um bom resultado R², embora o erro quadrático médio esteja em um valor bom. Minha hipótese é que o processo de realizar dummies não fosse tão necessário para a análise.

## Agradecimentos

Agradeço a oportunidade e adoraria fazer parte da equipe e aprender muito com vocês. Também amaria uma ajuda para entender a forma certa de tratar os dados e ter um bom modelo ao final.