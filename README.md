![image](https://github.com/LerinaMM/score_credito_clientes_data_science/assets/83770121/25e687ea-0252-4be9-8409-bf9bca7dfaf7)

# ✅ Score Crédito Clientes

Projeto foi desenvolvido para aprendizado através da Jornada Python da Hashtag Treinamentos

Voce foi contratado por um banco para conseguir definir o score de credito de clients. Voce precisa analisar todos os clientes do banco e, com base nessa analise, criar um modelo que consiga ler as informações do cliente e dizer automaticamente o score de credito dele através dos status: BOM, OK e RUIM

O score de crédito é uma medida da probabilidade de um indivíduo pagar suas dívidas. Ele é usado por credores para determinar se devem ou não conceder um empréstimo e a taxa de juros que devem cobrar. Os modelos de inteligência artificial podem ser usados para melhorar a precisão dos scores de crédito. Eles podem fazer isso analisando grandes quantidades de dados de crédito e identificando padrões que os humanos não podem ver. Os modelos de inteligência artificial também podem ser usados para personalizar os scores de crédito, levando em consideração fatores individuais, como histórico de emprego e renda. Como resultado, os modelos de inteligência artificial podem ajudar a garantir que os indivíduos recebam empréstimos aos melhores termos possíveis.
Fonte:Bard

# 📖 Modelos de Machine Learning

# Árvore de decisão

Uma árvore de decisão é um modelo de aprendizado de máquina supervisionado que pode ser usado para classificação e regressão. Ele faz isso criando uma árvore de nós, onde cada nó representa uma decisão a ser tomada. O nó raiz da árvore representa a decisão mais importante, e os nós filhos representam decisões menos importantes. O modelo continua a dividir os dados até que todos os dados estejam em nós folha, que representam as classes ou valores previstos.

As árvores de decisão são um modelo relativamente simples de entender e implementar, e podem ser usadas para uma ampla gama de tarefas. No entanto, eles podem ser propensos ao overfitting, o que significa que eles podem aprender a se ajustar muito bem aos dados de treinamento e não generalizar bem para novos dados.

# K-nearest neighbors

O K-nearest neighbors (KNN) é um modelo de aprendizado de máquina não supervisionado que pode ser usado para classificação e regressão. Ele faz isso calculando a distância entre um ponto de dados e os k vizinhos mais próximos. O ponto de dados é então atribuído à classe ou valor mais comum de seus vizinhos.

O KNN é um modelo relativamente simples de entender e implementar, e é relativamente robusto ao overfitting. No entanto, ele pode ser lento para treinar e pode não ser tão preciso quanto outros modelos para grandes conjuntos de dados.

# 💪 Fonte

Base de dados utilizada - (https://drive.google.com/drive/folders/1FbDqVq4XLvU85VBlVIMJ73p9oOu6u2-J)

# 💾 Dados

| Column     | Description              |
|------------|--------------------------|
| `mes` | mes de realização do cadastro |
| `idade` | Idade do indivíduo. |
| `profissao` | Profissão do individuo. |
| `salario_anual` | valor total ano do salario do empregado. |
| `num_contas` | Montante de contas que o individuo possui. |
| `num_cartoes` | Numero de cartões de credito que o indivíduo possui |
| `juros_emprestimo` | Juros aplicados caso o individuo tenha solicitado emprestimo. |
| `num_emprestimos` | Quantidade de emprestimos que o individuo possui. |
| `dias_atraso` | Dias de atraso de pagamento de dívidas. |
| `num_pagamentos_atrasados` | quantidade de pagamentos que estão em atraso que o individuo possui. |
| `num_verificacoes_credito` | numero de verificacoes para a solicitação de credito. |
| `mix_credito` | . |
| `divida_total` | Valor do montante da dívida que o indivíduo possui. |
| `taxa_uso_credito` | Taxa do credito que o individuo esta pagando. |
| `idade_historico_credito` | Tempo na qual foi solicitado o credito. |
| `investimento_mensal ` | . |
| `comportamento_pagamento` | Taxa do credito que o individuo esta pagando. |
| `saldo_final_mes` | Saldo da dívida no final do mês. |
| `score_credito` | Classificação do individuo relativo ao score de credito, se seria bom, ruim e normal. |
| `emprestimo_carro` | Se o individuo possui emprestimo de carro. |
| `emprestimo_casa` | Se o individuo possui emprestimo para a compra de casa. |
| `emprestimo_pessoal` | Se o individuo possui emprestimo pessoal. |
| `emprestimo_credito` | Se o individuo possui emprestimo de credito para outros fins. |
| `emprestimo_estudantil` | Se o individuo possui emprestimo para pagamento de estudo. |

# 🎯 Objetivo

Elaborar um modelo de Machine Learning para a concessão de credito. Encontrar o modelo com melhor desempenho e aplicar o modelo escolhido com novos dados de clientes

