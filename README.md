# IBGE_extracao_dados
O objetivo é extrair todos os dados referentes aos municípios da  região do Alto Solimões no Estado do Amazonas, a saber : Atalaia do Norte, Amaturá, Benjamim Constant, Fonte Boa, Jutaí, Santo Antônio do Içá, São Paulo de Olivença, Tonantins, Tabatinga.


1. Execute api.ipynb:
    Este arquivo tem o objetivo de extrair a lista de categorias dos dados referentes aos municípios, 
e então salva todos em um arquivo 'categorias.xlsx' , logo o código lerá este arquivo e gerará sumário das pesquisas referente a cada categoria em um diretório "./database/sumario"

2. Execute generate.ipynb para ler os sumarios e realizar o download das respectivas pesquisas.
3. Então Execute clean.ipynb para gerar um único arquivo contendo todas as pesquisas tratadas.
