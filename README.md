<h1 align="center">Alurinha - Flexbox</h1>

<p align="center">Curso Alura: Flexbox - Posicione elementos na tela.</p>

<h2>Principais diferenças entre as nossas propriedades de posicionamento</h2>

<h3>display: inline</h3>
<p align="justify">Colocando display: inline nos elementos permite eles se posicionarem um do lado do outro, o problema do display: inline é que os elementos não aceitam mais que seja modificada tanto a width quanto a height. Isso limita MUITO nossas possibilidades.</p>

<h3>display: inline-block</h3>
<p align="justify"> display: inline-block permite os elementos se posicionarem um do lado do outro porém, diferentemente do display: inline ele permite que os elementos tenham sua width e height modificadas. Por esse motivo o display: inline-block é muito mais interessante na maioria dos casos do que o display: inline.</p>

<p align="justify">O problema de usar display: inline-block é espaçar os elementos entre si. Para fazer isso teríamos que colocar margins e fazer contas.</p>


<h3>float: left | right</h3>
<p align="justify">O float é mais complicado, ele empurra o elemento para um dos lados (left | right) e os elementos que estão embaixo sobem. Isso nem sempre é o que a gente quer. Além do mais o float não permite que usemos a propriedade vertical-align: middle para alinhar os elementos verticalmente. Ou seja, para contornar isso uma possibilidade seria ter que colocar margin-top ou bottom nos elementos e usar os temidos números mágicos!</p>

<h3>display: flex</h3>
<p align="justify">O display: flex veio com o intuito de facilitar nossa vida nesses aspectos de posicionamento. Ele permite os elementos ficarem um do lado do outro, permite espaçar os elementos de forma mais intuitiva e sem ter que fazer cálculos. Além disso ele também permite alinhar os elementos verticalmente de forma fácil.</p>

<p align="justify">O display flex pode ser um pouco mais complicado de usar tendo em vista que existem diversas propriedades que vem junto da especificação flexible box, todavia tudo isso foi feito para justamente melhorar nosso código.</p>

<h2>Propriedades Flex</h2>

<h3>container:</p>

* display: flex
* flex-direction
* justify-content
* flex-wrap
* flex-flow
* align-items
* align-content

<h3>flex item:</p>

* order
* flex-grow
* flex-shrink
* flex-basis
* flex
* align-self