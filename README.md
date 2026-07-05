# Artigo-Métodos-Quantitativos-Aplicados
Da# Regularidade do Corpo Docente nos Municípios Brasileiros

Este repositório contém a base consolidada e os códigos utilizados nas análises do estudo sobre os determinantes da Regularidade do Corpo Docente nos municípios brasileiros.

## Base de dados

A base principal está localizada na pasta `dados`:

`dados/painel_ird_municipios_enriquecido.csv`

## Unidade de análise

Município-ano.

## Período analisado

2013 a 2024.

## Variável dependente

- IRD: Indicador de Regularidade do Corpo Docente.

## Variáveis explicativas

- ICG: Indicador de Complexidade da Gestão Escolar.
- AFD: Adequação da Formação Docente.
- IED: Indicador de Esforço Docente.
- ATU: Média de alunos por turma.
- LN_ESC: logaritmo do número de escolas públicas do município.

## Modelo principal

O modelo principal é estimado por Efeitos Fixos, com efeitos de município e de ano, e erros-padrão robustos clusterizados por município.

## Reprodução dos resultados

O notebook em Google Colab lê a base diretamente a partir do link público do GitHub. Dessa forma, os resultados podem ser reproduzidos sem acesso ao Google Drive da autora.

Para reproduzir:

1. Abrir o notebook no Google Colab.
2. Executar as células em sequência.
3. A base será carregada automaticamente pelo link público.
4. As tabelas e diagnósticos serão gerados no próprio ambiente do Colab.dos e códigos do artigo sobre IRD municipal
