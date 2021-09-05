Best fit é um algoritmo de gerenciamento de memória. Seu funcionamento consiste em alocar o bloco no menor espaço que seja suficientemente grande naquele bloco. Esse algoritmo é um pouco lento por ter que fazer diversas comparações, porém previne diversos erros.

Meu projeto simula o funcionamento desse algoritmo. Com ele podemos ver visualmente o que acontece.

Ele é composto por um array de 100 espaços que representa a memória. Todo número "-1" representa a um espaço livre, já qualquer outro número, representa o "id" de um processo. Cada processo pode ter tamanho variado, e por isso provavelmente, encontraremos no array valores com o mesmo id, representando assim, o tamanho daquele processo.

O programa faz a alocação dos processos automaticamente e aleatoriamente, podendo cada processo ter um tamanho entre 1 e 5

O  programa cria 2 processos e em seguida apaga um aleatoriamente (Por essa razão existe o array que guarda os valores dos ids dos processos alocados na memória naquele momento).

Para alocar cada processo, o programa faz uma serie de verificações que resulta no melhor lugar para alocar aquele processo.

Por fim, todos os passos são impressos no console, assim, temos uma representação visual de seu funcionamento

Projeto feito por Felipe Scherer
Licença- uso livre porém colocar meu nome nos créditos.
