Cap 1 - Conhecendo o JavaScript

DevTools: 
	A ferramenta DevTools presente nos navegadores web é de grande ajuda para comunidade de desenvolvedores web, a ponto de serem apelidados carinhosamente de “melhor amiga/o” da pessoa desenvolvedora. Através dessa ferramenta, conseguimos editar a aplicação em tempo de execução, adicionar ou remover tags HTML, mexer no CSS da página, escrever código JavaScript no console e ver as modificações sem persistência, porém sem alterar o código fonte real.

	Diferente do método tradicional para resolver problemas do código fonte que consistia em abrir o código e olhar linha a linha para descobrir o erro, o DevTools apresenta uma maneira mais simples e direta do problema no código, bastando acessar a aba Console que lá estará indicando o tipo e o arquivo onde se encontra o erro.

Para saber mais: HTML x CSS x JavaScript:
	Para que fique mais claro o porquê de se utilizar arquivos separados para HTML e JavaScript, leia o artigo da instrutora Rafaella Ballerini, que explica a diferença entre essas linguagens.

Artigo: HTML X CSS X JavaScript. Quais as diferenças?
https://www.alura.com.br/artigos/html-css-e-js-definicoes

O que aprendemos?:

Nessa aula, você aprendeu:

    Clicando no botão: 

Conhecemos a tag audio do HTML e como ela funciona, também como adicionar código JavaScript inline a partir do atributo onclick na tag button, e também como é a função alert() do JavaScript.

    Conectar JS com HTML: 

Aprendemos porque devemos ter arquivos dedicados para cada linguagem, e a extensão .js para arquivos com JavaScript, porque chamamos o nosso arquivo principal de JavaScript de main.js, e também, como fazemos para inserir um arquivo .js dentro de uma página HTML com a tag script.

    Buscar um elemento:

Aprendemos os tipos de seletores que podemos usar no JavaScript (elemento, classe e id), como utilizar a função querySelector para selecionar os elementos da nossa página HTML. Vimos nesta aula a referência document, que representa o documento HTML dentro do JavaScript, e o significa o Reference Error e como solucionar, além de entender que o JavaScript é uma linguagem case sensitive, e uso do operador ponto final para entrar dentro de referências como o document, e que o ponto e virgula é opcional porém recomendado.

Cap 2 - Funções

O local da tag script?:
Como vimos nesta aula, é possível inserir um arquivo JavaScript em dois locais do documento HTML, dentro da tag head ou da tag body. evemos colocar o JavaScript dentro da tag body logo antes do seu fechamento, </body>, quando o script depende de elementos do body já carregados pelo navegador.

O que aprendemos?

Nesta aula, você aprendeu:

    Play no JS: 

Como manipular a tag <audio> do HTML através do JavaScript, como selecionar um elemento a partir de um seletor de id e a reproduzir um som a partir da função play(). Além disso, viu também como os erros são apresentados na aba Console da ferramenta DevTools.

    O que é uma função?: 

O que é uma função, para que servem, como declará-la e sua sintaxe básica. Além disso, viu que a ordem de execução de um código JavaScript importa, desde a inserção da tag script antes do fechamos da tag </body> no HTML até a ordem do código JavaScript dentro do seu próprio arquivo.

    Clique no botão: 

A utilizar o onclick como atributo no JavaScript, e como atribuir uma função ao onclcik sem que esta função seja invocada imediatamente.


Cap 3 - Listas
Porque o document.querySelectorAll()?
	Como vimos durante a aula, apesar de utilizarmos o script document.querySelector(seletor) para capturar elementos do HTML individualmente, no Alura MIDI, trocamos ele pelo document.querySelectorAll(seletor).

Desta forma, o uso do document.querySelectorAll se justifica por utilizamos o document.querySelectorAll() para selecionarmos todos os elementos do seletor desejado, reduzindo a quantidade de repetição de código, que consequentemente, promoverá uma otimização no código em alternativa a repetição.

O que aprendemos? 
	
Nessa aula, você aprendeu:

    Lista de elementos: 

O que são os comentários de código e como utilizá-los para auxiliar durante a escrita da nossa aplicação. Vimos também uma alternativa ao querySelector quando necessário buscar muitos elementos, que é o querySelectorAll, que retorna uma lista (NodeList) com todos os elementos do seletor informado evitando a repetição de código.

    Referências: 

Para que serve uma referência e como declaramos uma referência de valor constante no código.

    Conhecendo listas: 

A estrutura de uma lista em JavaScript e como podemos acessar os elementos a partir dos índices com a sintaxe do colchetes.

Cap 4 - Iterando em listas

Porque usamos os while?

Assim como em outras linguagens de programação, o JavaScript também tem o while que é uma das formas de trabalhar com estruturas de repetição. Foi necessário usar o while como estrutura de repetição para auxiliar o acesso a cada elemento dentro da lista de teclas, podendo aplicar a rotina de associar uma função no atributo onclick de cada um destes elementos. Para trabalhar com a lista de teclas, esta estrutura possibilita que uma variável de contador tenha seu valor incrementado a cada repetição, e que pode ser utilizado para acessar os indices de uma lista além de ser comparado com o tamanho de lista, formando a condição para a repetição cessar.

O que é parâmetro de uma função?

A função é o conjunto de instruções de código, que executa uma determinada tarefa, que é utilizada somente quando chamada/invocado, podendo receber parâmetros ou não. Os parâmetros são os nomes que damos a valores que uma função pode receber em sua chamada, que podem ou não ter um valor padrão. Os parâmetros de uma função são como variáveis ficam disponíveis apenas no corpo da função.
Os parâmetros servem para auxiliar em alguma lógica no código dentro de uma função. Por exemplo, uma função calculaMedia(), pode ter como parâmetros notaA e notaB, que serão os valores utilizados para serem caclulados e retornar o valor da média.

O que aprendemos?

Nessa aula, você aprendeu:
Percorrendo uma lista:
Como percorrer uma lista usando a estrutura de repetição while, a criar referências variáveis com let, e como incrementar o valor de uma variável, e criar uma condição para evitar o loop infinito, também conhecemos o atributo length contido nas listas que nos ajudou a obter dinamicamento o valor do tamanho de uma lista.

Função com parâmetros:
Como declarar e utilizar parâmetros dentro de uma função que criamos, e o que é uma função anônima e o retorno undefined de uma função.

Textos dinâmicos:
Como criar textos dinâmicos utilizando template string e como acessar as classes de um elemento através do atributo classList.

Repetição otimizada com For:
Como é a estrutura de repetição for e como ela pode nos ajudar com um código mais limpo, além da forma de incrementar um valor de variável com o operador ++.

Cap 5 - Eventos e lógicas

O que aprendemos?

Nessa aula, você aprendeu:
Eventos no teclado:
O que são eventos do teclado e como usá-los: onkeydowne onkeyup. Como adicionar e remover classes em um elemento HTML através do JavaScript, com as funções add e remove do classList.

Condições no código e operadores lógicos:
O que é o objeto event, como declarar e acessar ele através do parâmetro de uma função atrelada a um evento. A estrutura condicional if e para que ele serve, além de conhecer o operador de igualdade ==, estritamente igual (===), e o operador or (||).

Mais condições:
A estruturas condicionais if e else juntas. O operador not equals (!=), operador lógico and (&&) e o valor null.