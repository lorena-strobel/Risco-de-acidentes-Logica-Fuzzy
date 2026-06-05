# Risco-de-acidentes-Logica-Fuzzy

## Descrição do projeto
Este projeto tem como objetivo desenvolver um sistema especialista baseado em Lógica Fuzzy para avaliar o risco de ocorrência de acidentes de trânsito.

O sistema utiliza informações relacionadas às condições de condução, como velocidade do veículo, condição da pista e visibilidade, para estimar o nível de risco de acidente.

A Lógica Fuzzy foi escolhida por permitir representar situações reais de forma mais próxima do raciocínio humano, tratando conceitos subjetivos como "velocidade alta", "visibilidade ruim" e "pista escorregadia".

## Objetivo
Desenvolver uma aplicação prática utilizando Lógica Fuzzy capaz de determinar o nível de risco de acidente a partir de fatores que influenciam diretamente a segurança no trânsito.

O sistema deverá:

Receber valores de entrada referentes às condições de condução;
Aplicar regras fuzzy definidas pelos autores;
Realizar o processo de inferência fuzzy;
Efetuar a defuzzificação;
Apresentar um índice de risco compreensível para o usuário.

## Abordagem adotada
O sistema foi implementado utilizando o método de inferência Mamdani.

As etapas consistem em:

1. Definição das variáveis linguísticas;
2. Construção das funções de pertinência;
3. Criação das regras fuzzy;
4. Inferência Mamdani;
5. Defuzzificação pelo método do centroide;
6. Interpretação do resultado final.

## Estrutura de Pastas
```text
Risco-de-acidentes-Logica-Fuzzy/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── avaliacao_risco_acidentes.ipynb
│
├── src/
│   ├── fuzzy_system.py
│   ├── membership_functions.py
│   └── rules.py
│
├── images/
│   ├── pertinencia_velocidade.png
│   ├── pertinencia_pista.png
│   └── pertinencia_visibilidade.png
│
└── docs/
    └── relatorio.pdf
```
