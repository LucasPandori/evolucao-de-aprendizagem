## Conteúdos a serem trabalhados nesse módulo:

- Funções
- Tipos de dados II

## O que eu já sei sobre os assuntos que serão abordados nesse módulo?

- Função é uma forma de não precisar reescrever o mesmo código várias vezes, criando-o apenas uma vez e chamando toda vez que precisar usar as instruções que estão dentro dele. Para retornar algun valor é preciso usar o return e para usar a função precisa chamar a função pelo nome dado e colocar dentro dos parênteses os valores que serão usados.

- Eu sei sobre os tipos de dados do tipo string, number, booleano, object e como usá-los no typescript, para tipar e não deixar que o código use outro tipo de dado errado ao invés do certo( exemplo: era para ser usado um number e acaba sendo usado uma string e ao invés de somar concatene ).

## O que quero aprender sobre os assuntos que serão abordados nesse módulo?

- Gostaria de aprender outras funcionalidades, caso tenha alguma, e desenvolver a lógica certa para usá-lo.
- Quero aprender sobre novos tipos de dados que talvez existam e outras formas de tipagem que possa ajudar ou ao menos facilitar na hora de escolher o tipo de dado certo para o código não dar erro.

## Minha evolução: o que aprendi sobre os assuntos que foram abordados nesse módulo?

- Aprendi que posso executar uma função sem parâmetro, apenas chamando-a e abrindo e fechando parênteses. Outras coisas que eu aprendi foi que caso a variável tenha o mesmo nome que o parâmetro, eu posso apenas colocar o nome uma vez que a máquina ja entende que aquela variável vai receber o valor do parâmetro de nome igual; o return não mostra nada no terminal, pois precisa do console.log para mostrar; tudo que estiver depois do return não será mostrado, mesmo com console.log; uma nova funcionalidade usando o arrow function e a fazer a tipagem dos parâmetros e do return da função.
- Na aula de tipos de dados II, eu aprendi sobre os tipos literais, união de tipos, conjuntos, tuplas, o Norrowing, assertion e unknowm. Os tipos literais são tipos de dados, mas ao invés de ser os tradicionais (number,string,boolean) o programador pode escolher um valor específico, por exemplo: o programador quer que a variável sempre seja 1, ele coloca o tipo dela como o número 1 e então ela não pode ser outra coisa além de um. A união seria o "ou", onde o programador quer colocar dois tipos de dados ( string | number ) permitindo o código receber dois tipos de dados, o conjunto seria o "e" (string & boolean )que é parecido com o "ou" porém com uma diferença,o valor precisa ser necessariamente esses dois, não pode ser um ou outro. As tuplas é quando o programador põe o tipo de dado de cada elemento do array na mesma ordem do array. O narrowing é um tipo de estreitamento, onde se usa o código typeof (typeof SUA_VARIÁVEL) para ver o tipo de dado que está sendo recebido e assim fazer alguma coisa para não dar erro ou retornar algum valor errado, por exemplo usar o typeof para ver se está recebendo um dado tipo number ou tipo string, se for tipo number realizar uma soma, se for tipo string transformar em um number e somar. O assertion ( SUA_VARIÁVEL as number ) é uma forma do programador forçar o código aceitar algum valor ou forçar a atribuição de algum valor para uma variável. E por fim o unknowm (desconhecido) que é melhor do que se usar any, ou seja, é melhor colocar como "desconhecido" ao invés de colocar como "qualquer coisa"
