# IA-Checkpoint-1

Primeira prova de Inteligência Artificial do ano, cujo objetivo é avaliar conceitos sobre Modelagem de dados e Aprendizado de Máquina (ML).

Erros a serem corrigidos:
- No ex2, converti as milhas/1000 para quilometros/1000. Para ter o valor correto da quilometragem, ainda teria que multiplicar por 1000 novamente.
- No ex 7.2 usei o knn mas no modelo de classficação para o caso de regresão, deveria usar o KNeighborsRegressor. Mesmo conceito de algoritmo, mas com outra aplicação. 
- No ex8, apesar do conceito está certo, a chamada do modelo está errada. Precisaria ser chamado o metodo predict: pred = lreg.predict([[2005, 172095, 2.0, 6, 1]]).
