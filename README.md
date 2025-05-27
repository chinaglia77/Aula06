# Aula 06 - CSS Grid Layout

Este projeto é um exemplo prático de como usar o **CSS Grid Layout** para organizar elementos HTML em linhas e colunas, com diferentes tamanhos e espaçamentos.

---

## Sumário

- [O que é CSS Grid?](#o-que-é-css-grid)
- [Como o projeto está estruturado](#como-o-projeto-está-estruturado)
- [Explicação do código HTML](#explicação-do-código-html)
- [Explicação do CSS](#explicação-do-css)
- [Conceitos importantes](#conceitos-importantes)
- [Como usar](#como-usar)
- [Referências](#referências)

---

## O que é CSS Grid?

O **CSS Grid** é um sistema bidimensional de layout em CSS que permite criar facilmente estruturas com linhas e colunas. Ele facilita a organização dos elementos da página, oferecendo maior controle sobre espaçamentos, alinhamentos e tamanhos.

---

## Como o projeto está estruturado

- **index.html** — arquivo HTML com a estrutura da página
- **css/style.css** — arquivo CSS com os estilos e regras do Grid

---

## Explicação do código HTML

```html
<main class="grid linha">
    <div class="grid coluna">
        <div class="box box-01">BOX 1</div>
        <div class="box box-02">BOX 2</div>
        <div class="box box-03">BOX 3</div>
    </div>

    <div class="grid coluna-2">
        <div class="box box-04">BOX 4</div>
        <div class="box box-05">BOX 5</div>
    </div>

    <div class="grid coluna3">
        <div class="box box-06">BOX 6</div>
        <div class="box box-07">BOX 7</div>
    </div>

    <div class="box box-08">BOX 8</div>
    <div class="box box-09">BOX 9</div>
    <div class="box box-10">BOX 10</div>
    <div class="box box-11">BOX 11</div>
    <div class="box box-12">BOX 12</div>
</main>
