1.Ao realizar tal alteração o sistema fica travado a parte de escrever <h2>Dados obtidos do servidor!</h2>.

2.O problema ocorre pois mesmo sendo uma função assincrona sua estrutura ainda trabalha como uma linguagem estruturada e com o comando estando na parte de baixo da função so retorna quando a mesma é retornado junto dos dados.

3. simplesmente alterei o local para o primeiro comando ser ele, assim "destravando" a aplicação.
