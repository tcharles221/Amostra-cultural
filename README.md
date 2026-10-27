# Amostra-cultural
Trabalho da Amostra cultural
 Projeto: Controle de Estoque de uma Lojinha com Python

Este repositório contém um script que fiz para a disciplina de Análise e Método para Sistemas. O programa controla o estoque de uma lojinha de materiais escolares: mostra os produtos, calcula o valor total, simula vendas e avisa quais produtos precisam ser repostos.

🛠 Tecnologias Utilizadas
Linguagem: Python 3.x
Conceitos Praticados: Estruturas de dados (Dicionários e Listas), funções, laços de repetição (for) e condicionais (if)
🧠 Como o programa funciona
O estoque é um dicionário, onde cada produto tem preço e quantidade.
A função mostrar_estoque mostra todos os produtos na tela.
A função valor_total soma preço × quantidade de cada produto.
A função vender segue uma regra: só vende se tiver quantidade suficiente no estoque.
A função produtos_em_falta cria uma lista com os produtos que têm menos de 5 unidades.
💻 Como Executar o Script
Certifique-se de ter o Python instalado em seu computador.
Baixe ou clone este repositório.
No terminal ou prompt de comando, execute o arquivo:
bash
   python script.py
✅ Exemplo de Resultado
=== ESTOQUE ATUAL ===
Caderno: 20 unidades - R$ 15.90 cada
Caneta: 3 unidades - R$ 2.50 cada
Mochila: 5 unidades - R$ 89.99 cada
Lapis: 2 unidades - R$ 1.20 cada
Borracha: 15 unidades - R$ 1.80 cada

Valor total em estoque: R$ 804.85

=== SIMULANDO VENDAS ===
Venda realizada: 2 de Mochila.
Venda negada: so tem 3 de Caneta.

=== PRODUTOS PARA REPOR ===
- Caneta
- Mochila
- Lapis

A venda de 10 canetas foi negada porque só havia 3 no estoque. Depois das vendas, a mochila ficou com 3 unidades e entrou na lista de reposição.
