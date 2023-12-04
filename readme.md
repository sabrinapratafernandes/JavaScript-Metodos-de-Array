# JavaScript: Metodos de Array

Curso em andamento

## Notas: 

### Método fetch()

- Uma API moderna;
- Usado para fazer requisições HTTP e recuperar recursos em uma rede;
- Retorna uma promisse, que permite encadear métodos then(), parar manipular diferentes etapas do processo assíncrono;
- Não trata automaticamente erros de rede ou HTTP (exemplo: 404/500);
- O catch() é usado para lidar com erros. 

### Método forEach()

- Pega cada elemento do array e executa a função que será passada;
- Uma maneira de iterar sobre os elementos do array em JS;
- Executa uma função de callback fornecida uma vez para cada elemento no array, em ordem;
- Recebe o elemento atual, o índice e o array completo como argumentos.

### Método map()

Invoca a função callback passada por argumento para cada elemento do array e devolve um novo array como resultado. 

- Invocada da mesma forma que o forEach();
- Diferente do forEach() retorna um valor;
- Não altera o array original; 
- Cria e retorna um novo array.


### Função callback

Função que é passada como argumento para outra função. 

- Utilizada especialmente em operações assíncronas;
- Permite especificar o que deve acontecer após conclusão de uma operação assíncrona;
- Usada para evento e manipulação de array. 

### Método filter()

Cria um novo array com os elementos que passam passam por um teste implementado por uma função de callback fornecida. 

- Filtra os elementos do array com base em uma condição especifica. 
- Não altera o array original, retorna um novo array apenas com os elementos que atendem a condição especificada. 

### Método reduce()

Método de array, usado para reduzir os elementos de um array a um único valor. Ele usa uma função callback para cadaelemento do array, acumulando um resultado final. 

Pode ser utilizado para uma variedade de operações, como encontrar o valor máximo ou minimo, concatenar strings, contar ocorrências e mais. 

### Método sort()

Não é uma ordenação estável, ou seja, não é a ordenação esperada necessariamente, o tempo de execução depende da quantidade de memória que será utilizada. 

- Usado para ordenar os elementos de um array;
- altera o array original;
- ordena de forma simples com base nos valores unicode nos caracteres;
- para uma ordenação mais complexa, especialmente para números, é possível fornecer uma função de comparação como argumento para o método sort()
- sem a função de comparação o sort() cpnverte os elementos do array para strings e compara seus valores unicode, ao lidar com números é recomendável passar uma função de comparação. 

### Unicode

É um padrão que atribui um número unico (ponto de código) a cada caractere, abrange praticamente todos os sistemas de escrita do mundo. A codificação permite representar textos em diferentes idiomas e incluí simbolos especiais. Esses pontos de código são representados em hexadecimal. 

Exemplos: 

- Caractere A : Ponto de código Unicode U+0041
- Caractere Ç : Ponto de código Unicode U+00E7








