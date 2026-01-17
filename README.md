# Lista-ligada
Demonstrando a implementação do conceito de lista ligada. O código em questão foi escrito em linguagem C e consiste em criar estruturas ou structs chamados "nós" para ligar uma informação ou
item de uma lista no seguinte com o uso de ponteiros, sendo que o ponteiro aponta para o próximo item da lista, esse item também vai ter um ponteiro que aponta para o próximo item e assim
sucessivamente até chegar ao final da lista, em que o último item não aponta para o próximo, pois não tem próximo, então ele aponta para o vazio ou "null". Usar listas ligadas envolve a
manipulação e a alocação de memória de forma dinâmica, por isso usamos expressões como o "malloc", que significa "memory allocation" ou "alocação de memória", essa expressão permite que seja
reservado exatamente a quantidade de memória necessária para o que você precisa fazer, de modo que você não precisa declarar anteriormente quantos itens você vai usar de forma estática, isso
não permitiria a mudança no tamanho sem mudar o código, mas com o malloc isso é possível. A única questão é que quando se usa o malloc você reserva um espaço na memória, mas não o libera
automaticamente após o uso, a memória continua sendo usada, e se não tomar cuidado podemos ter um "memory leak" ou vazamento de memória, por isso usamos a expressão "free" seguida da
variável cujo espaço na memória nós queremos liberar escrita entre parênteses, depois de terminar de usar a variável e não precisar mais armazenar ela, você usa o free para liberar a
memória, isso otimiza o uso da memória da máquina, é uma boa prática na programação.
