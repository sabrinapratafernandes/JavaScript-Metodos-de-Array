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







