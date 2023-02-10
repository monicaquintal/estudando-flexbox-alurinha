<div align="center">
<a href="https://github.com/monicaquintal" target="_blank"><img align="right" height="160" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain-wordmark.svg" /></a>
<h2>Alurinha</h2>
<h3>Curso: Flexbox - Posicione elementos na tela (Alura)</h3>
<p>ONE | Fase 3 - Especialização Front-End</p>
</div>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-repositorio">Aulas</a>
</p>
<br>

## 🚀 Tecnologias

Projeto desenvolvido com as seguintes tecnologias:

- HTML
- CSS 

## 💻 Projeto

A proposta do curso é o desenvolvimento do Alurinha, um gerenciador de cursos online, sobretudo manuseando o flexbox, que é uma especificação CSS.

## 🔖 Layout

<br>
<p align="center">
  <img alt="projeto Alurinha" src="./layouts/alurinha-layout-desktop.png" width="50%">
</p>
<br>

## 📚 Aulas

### Aula 01: Preparando o ambiente

### Aula 02: Ajustando o cabeçalho
- criando e importanto o arquivo flexbox.css:

~~~html 
<link rel="stylesheet" href="./css/flexbox.css">
~~~

- ajustes de display flex.

~~~css
.pai {
  display: flex;
}
~~~

- disponibilizado site [Can I Use](https://caniuse.com/) para verificar em quais sistemas/navegadores a propriedade Flexbox funciona, já que é uma propriedade razoavelmente atual.
- importante:
  - display: inline
    - permite que os elementos se posicionem um do lado do outro.
    - o problema é que os elementos não aceitam mais que seja modificada tanto a width quanto a height, o que limita MUITO as possibilidades.
  - display: inline-block
    - permite que os elementos se posicionem um do lado do outro.
    - permite que os elementos tenham sua width e height modificadas! 
    - é muito mais interessante na maioria dos casos do que o display: inline.
    - o problema de usar display: inline-block é espaçar os elementos entre si. Para fazer isso teríamos que colocar margins e fazer contas.
  - float: left | right
    - é mais complicado, empurra o elemento para um dos lados (left | right) e os elementos que estão embaixo sobem.
    - não permite que usemos a propriedade vertical-align: middle para alinhar os elementos verticalmente. 
    - para contornar a falta do vertical-align, uma possibilidade seria colocar margin-top ou bottom nos elementos e usar os números mágicos!
  - display: flex
    - permite os elementos ficarem um do lado do outro, permite espaçar os elementos de forma mais intuitiva e sem ter que fazer cálculos. Além disso ele também permite alinhar os elementos verticalmente de forma fácil.
    - pode ser um pouco mais complicado de usar tendo em vista que existem diversas propriedades que vem junto da especificação flexible box, todavia tudo isso foi feito para justamente melhorar nosso código.

### Aula 03: