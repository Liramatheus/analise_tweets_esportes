# Coleta e Análise de Tweets sobre Esportes

Este projeto foi desenvolvido como parte de uma atividade avaliativa da faculdade, com o objetivo de aplicar conhecimentos de **coleta de dados via API**, **limpeza de texto**, **análise de frequência** e **classificação de sentimentos**.

## Tema

**Esportes** — foram coletados 50 tweets recentes contendo essa palavra.

## Tecnologias Utilizadas

- **Python**
- **Google Colab**
- `requests` – para acessar a API do Twitter (X)
- `re` – para limpar o texto
- `collections.Counter` – para contar palavras
- `nltk.vader` – para análise de sentimentos

## Etapas do Projeto

1. **Coleta dos Tweets:** Utilizando a API do Twitter com `Bearer Token`.
2. **Limpeza do Texto:** Remoção de menções, hashtags, links, pontuação e normalização.
3. **Frequência de Palavras:** Identificação das palavras mais comuns nos tweets.
4. **Análise de Sentimentos:** Classificação dos tweets em Positivos, Negativos e Neutros usando VADER.

## Resultados

> *Valores fictícios — substitua pelos reais do seu notebook se quiser dar mais força pro portfólio.*

- Tweets analisados: 50
- **Neutros:** 28
- **Positivos:** 15
- **Negativos:** 7

### Palavras mais comuns:
- futebol
- jogo
- time
- vitória
- campeonato

## Autor

**Matheus Lira**

[LinkedIn](https://www.linkedin.com/in/matheus-lira-5036b11b8/)
