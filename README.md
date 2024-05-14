## Conteúdos a serem trabalhados nesse módulo:

- Funções
- Tipos de dados II
- Gestão de tempo
- Tipos Utilitários
- Métodos de strings

## O que eu já sei sobre os assuntos que serão abordados nesse módulo?

- Função é uma forma de não precisar reescrever o mesmo código várias vezes, criando-o apenas uma vez e chamando toda vez que precisar usar as instruções que estão dentro dele. Para retornar algun valor é preciso usar o return e para usar a função precisa chamar a função pelo nome dado e colocar dentro dos parênteses os valores que serão usados.

- Eu sei sobre os tipos de dados do tipo string, number, booleano, object e como usá-los no typescript, para tipar e não deixar que o código use outro tipo de dado errado ao invés do certo( exemplo: era para ser usado um number e acaba sendo usado uma string e ao invés de somar concatene ).

- Sei que gestão de tempo é muito importante, tanto para finalizar suas tarefas no prazo quanto para se ter uma vida mais organizada e conseguir lidar com imprevistos. Tenho conhecimento sobre alguns métodos de estudo, como método pomodoro, no qual eu já usei para melhorar meus estudos.

- Para ser sincero não sei nada sobre tipos utilitários.

- As strings são sequências de caracteres (letras, números, simbolos ) que com o auxilio de aspas simples ou duplas ( '', "" ) formam textos que podem ser armazenados em variáveis e serem concatenados para juntar dois ou mais textos.

## O que quero aprender sobre os assuntos que serão abordados nesse módulo?

- Gostaria de aprender outras funcionalidades, caso tenha alguma, e desenvolver a lógica certa para usá-lo.
  
- Quero aprender sobre novos tipos de dados que talvez existam e outras formas de tipagem que possa ajudar ou ao menos facilitar na hora de escolher o tipo de dado certo para o código não dar erro.
  
- Acharia interessante aprender sobre outros métodos de estudo que possa ajudar a me concentrar mais nos meus estudos e ferramentas que me ajudem a me organizar melhor.
  
- Quero descobrir o que são tipos utilitários, para que servem e onde posso usá-los.

- O que são métodos de strings, como posso usá-los e como isso pode me ajudar a criar códigos mais complexos e com mais facilidade.

## Minha evolução: o que aprendi sobre os assuntos que foram abordados nesse módulo?

- Aprendi que posso executar uma função sem parâmetro, apenas chamando-a e abrindo e fechando parênteses. Outras coisas que eu aprendi foi que caso a variável tenha o mesmo nome que o parâmetro, eu posso apenas colocar o nome uma vez que a máquina ja entende que aquela variável vai receber o valor do parâmetro de nome igual; o return não mostra nada no terminal, pois precisa do console.log para mostrar; tudo que estiver depois do return não será mostrado, mesmo com console.log; uma nova funcionalidade usando o arrow function e a fazer a tipagem dos parâmetros e do return da função.

- Na aula de tipos de dados II, eu aprendi sobre os tipos literais, união de tipos, conjuntos, tuplas, o Norrowing, assertion e unknowm. Os tipos literais são tipos de dados, mas ao invés de ser os tradicionais (number,string,boolean) o programador pode escolher um valor específico, por exemplo: o programador quer que a variável sempre seja 1, ele coloca o tipo dela como o número 1 e então ela não pode ser outra coisa além de um. A união seria o "ou", onde o programador quer colocar dois tipos de dados ( string | number ) permitindo o código receber dois tipos de dados, o conjunto seria o "e" (string & boolean )que é parecido com o "ou" porém com uma diferença,o valor precisa ser necessariamente esses dois, não pode ser um ou outro. As tuplas é quando o programador põe o tipo de dado de cada elemento do array na mesma ordem do array. O narrowing é um tipo de estreitamento, onde se usa o código typeof (typeof SUA_VARIÁVEL) para ver o tipo de dado que está sendo recebido e assim fazer alguma coisa para não dar erro ou retornar algum valor errado, por exemplo usar o typeof para ver se está recebendo um dado tipo number ou tipo string, se for tipo number realizar uma soma, se for tipo string transformar em um number e somar. O assertion ( SUA_VARIÁVEL as number ) é uma forma do programador forçar o código aceitar algum valor ou forçar a atribuição de algum valor para uma variável. E por fim o unknowm (desconhecido) que é melhor do que se usar any, ou seja, é melhor colocar como "desconhecido" ao invés de colocar como "qualquer coisa"

- Nesta aula conheci ferramentas que auxiliam na sua organização e comecei a usar o google agenda para me organizar. Compreendi o que é procrastinação,  reorganização e a saber qual dos dois eu estou fazendo, se estou procrastinando ou apenas reorganizando meu tempo. Além de ouvir relatos de meus colegas que teriam os mesmos pensamentos e problemas que eu, me fazendo refletir e encontrar uma possível solução para tais problemas.

- Tipos utilitários são tipos do typescript, que servem para facilitar transformações de tipo comum (Utilitário<tipo>). Os tipos que foram comentados em aula foram o Partial, Require, Readonly, Pick, Omit, Record, Exclude, Extract, Upercase, Lowercase e Capitalize.O Partial transforma todas as propriedades em opcionais, permitindo que não use uma propriedade; O Require faz com que as propriedade sejam todas obrigatórias e se elas forem opcionais ele as transformará em obrigatórias; Readonly é um tipo utilitário que não permite que você altere o valor de alguma propriedade; Pick(Pick<tipo, propriedade1 | propriedade2>) permite que o programador escolha quais propriedades do tipo vai ser usado, excluindo as propriedades que não foram escolhidas; Omit(Omit<tipo, propriedade_excluida1 | propriedade_excluida2>) este tipo utilitário permite que o programador escolha quais propriedades ele irá remover, usando apenas as propriedades que ele não selecionou; O Record (Record<chaves,tipo>) cria um type, onde todos as propriedades deste type criado vão ser do mesmo tipo comum (number, string, boolean); Exclude (Exclude<união_tipos, item_excluidos>) este tipo exclui um ou mais itens de uma união de tipos; O Extract (Extract<união_tipos, item_adicionado>) ao contrário do exclude, extrai o item da união de tipos; Upercase (Upercase<tipostring>) transforma todas as letras da string desse tipo em maiúsculas; Lowercase (Lowercase<tipostring>): transforma todas as letras da string desse tipo em minúsculas; Capitalize (Capitalize<tipostring>): transforma a primeira letra da string desse tipo em maiúscula.

- Métodos de strings são métodos onde é possível modificar strings que já foram criadas, criando novas strings a partir das existentes, mas com as modificações escolhidas de acordo com o método que foi usado. Os tipos de métodos comentados em aula  foram: **.trim()**: Cria uma nova string, a partir da string que você criou, eliminando todos os espaços do inicio ao fim; **.trimStar()**: remove todos os espaços apenas do início de uma string; **.trimEnd()**: remove todos os espaços apenas do fim de uma string; **.toUpperCase()**: Transforma os caracteres de uma string em caracteres maiúsculos; **.toLowerCase()**: Transforma os caracteres de uma string em caracteres minúculos; **.substring(indiceInicial, IndiceFinal)**: Retorna a parte de uma string a partir do indice inicial até final(opcional) e se o indiceFinal for maior que o indiceInicial ele inverte os valores; **.slice()**: Extrai uma parte de uma string de acordo com os indices que foram passados, mas os indices, tanto inicial quanto final, são opcionais, pode usá-lo sem passar os indices que ele irá retornar a string toda e quando é passado um valor negativo nos indices ele conta do final para o começo; **.split(separador, limite(opcional))**: Converte uma string em um array contendo os caracteres da string, incluindo os espaços, ou converte em um array contendo a string separada da maneira que o programador passar dentro dos parênteses; **.replace(stringTrocada, stringNova)**: substitui a primeira correspondência da string por outra; **.replaceAll(stringTrocada, stringNova)**: substitui todas  as correspondências da string por outra(disponivel a partir do ES2022); **.padStart(tamanhoMaximo, preenchimento)**: Completa o inicio da string com a correspondência, de acordo com o tamanho da string; **.padEnd(tamanhoMaximo, preenchimento(opcional))**: Completa o fim da string com o preenchimento, de acordo com o tamanho da string; **.includes(stringProcurada)**: Retorna um booleano (true ou false) caso encontre ou não uma correspondência em uma string ; **.indexOf(stringProcurada)**: Retorna a posição em que a correspondência da string está, caso não encontre nenhuma palavra correspondente, vai ser retornado o número -1.





 
