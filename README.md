# Jogo de Memória

## :scroll: Sumário

- [Sobre](#about)
- [Estrutura](#structure)
- [Conceitos](#learned)

## :computer: Sobre <a name = "about"></a>

Projeto consiste em um jogo de memória com tecnologias referente ao front-end

> Bootcamp 🚀 = Javascript Game Developer

<p align="center">
<br>
  <a href="https://web.digitalinnovation.one/" rel="noopener">
 <img width=800px height=400px src="https://hermes.digitalinnovation.one/site/images/cover_dio.jpg" alt="Logo Digital Innovation One"></a>
</p>

### :mag: Imagens do projeto

<p align="center">
 :globe_with_meridians: DEPLOY
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/lcds90/game-memory/development/img/screenshot.png">
</p>

## :file_folder: Estrutura do projeto <a name = "structure"></a>

```
 ├── game-memory
    ├── img                # Pasta de Imagens
    ├── index.html         # Estrutura do jogo
    ├── style.css          # Folha de estilo do jogo
    └── script.js          # Lógica do Jogo
```

<hr>

## :memo: Conceitos aprendidos <a name = "learned"></a>

### CSS

#### flex-wrap: wrap; 
Divide os elementos para irem para baixo.

#### calc
```
height: calc(33.333% - 40px);
width: calc(25% - 40px);
margin:20px;
```
O calculo é feito pois o margin acrescenta 20px em todos os lados, removendo 40px calcula topo/baixo e esquerda/direita

### perspective
Ela mostra a perspectiva do usuário no eixo z, sendo o efeito 3D
Quanto maior a perspectiva, maior o efeito 3D

### preserve-3d
```
transform-style: preserve-3d
```
Evita de cartas ficarem achatadas, evitando o 2D

### backface-visiblity
Todo elemento possui backface-visiblity, que o elemento ao contrario, seria ele mesmo espelhado

### display-flex order
Quando é invocado na estrutura, ele é ordenardo de acordo com o código fonte.

<hr>

### JS

#### document.querySelectorAll
Retorna um Array com todos os elementos encontrados no DOM

#### this
Faz parte do contexto da função, quando ela é chamada no projeto é a carta atual referente do querySelector

#### Desestruturação do Array
Na função resetBoard reseta os valores para seus estados iniciais.

#### Immediately Invoked Function
Ela é renderizada sempre quando invocada