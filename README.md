# Lista_exercicios1

1 - Os principais métodos são GET e POST. GET recebe dados e POST envia dados.

2 - Basicamente, nessa arquitetura, o cliente faz uma requisição ao servidor. 
O servidor recebe essa requisição, processa os dados e retorna uma resposta na forma de um documento HTTP,
que o cliente pode interpretar e exibir.

3 - O protocolo HTTP serve para realizar a comunicação entre o cliente e o servidor.

4 -

a) GET - responsável por receber os dados de um servidor; POST - responsável por enviar os dados de um servidor ; DELETE - exclui um recurso específico.

b) 200 - Requisição bem sucedida
404 - Recurso não localizado
500 - Erro interno no servidor

5 - O cliente poderia enviar uma nova requisição a cada instante para verificar se houve alguma mudança. 
Outra possibilidade seria o cliente fazer uma requisição e o servidor mantê-la aberta até que houvesse uma nova curtida ou e-mail. 
Assim que o servidor enviasse uma resposta, o cliente faria uma nova requisição,
que permaneceria em espera até que outra mudança acontecesse.
