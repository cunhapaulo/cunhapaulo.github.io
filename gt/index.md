---
Title: Repositório de Conteúdos Programados para o GT - Yvon Costa
author: Paulo Cunha
description: Repositório de conteúdos espíritas para estudo do Grupo de Transição.
keywords: Doutrina Espírita, UEP, Yvon Costa, Espiritismo
marp: true
---

<!-- 
    Styles got from Juan Vera del Campo at https://github.com/Juanvvc/markdown-slides
-->
<style>

h1 {
    color: blue;
}

section a {
    color: gray;
}

section blockquote {
    border-top: 0.1em dashed var(--extra-back-color);
    font-size: 70%;
    margin-top: auto;
}

:root {
    --main-color: #e65014;
    --darker-color: #e65014;
    --lighter-color: #e26c3e;
    --extra-back-color: rgb(175, 172, 172);
}

section.lead {
    background-color: var(--main-color);
    text-align: center;
    color: white;
    padding: inherit;
}
section.lead h1, section.lead h2, section.lead p, section.lead a {
    color: white;
    padding: 0.5em;
    background-color: inherit;
    margin-bottom: 0;
}
section.lead footer, section.lead header, section.lead:after {
    /* hide header, footer and pagination */
    display: none;
}
section.lead::before {
    /* logo in white */
    filter: invert(100%) saturate(0) brightness(1.8);
}
section.cool-list ol {
    counter-reset: li; /* Initiate a counter */
    list-style: none; /* Remove default numbering */
    padding: 0;
    /*text-shadow: 0 1px 0 rgba(255,255,255,.5);*/
}
section.cool-list li {
    margin-bottom: 0.1em !important;
    margin-top: 0.1em !important;
}
section.cool-list ol > li > em, section.cool-list > ol > li > a {
    position: relative;
    display: block;
    padding: .4em .4em .4em 2em;
    margin: .5em 0;
    background: #ddd;
    color: #444;
    text-decoration: none;
    border-radius: .3em;
    transition: all .3s ease-out;
    font-style: normal;
}
section.cool-list ol > li > em:before, section.cool-list > ol > li > a:before{
    content: counter(li);
    counter-increment: li;
    position: absolute;
    left: -1.3em;
    top: 50%;
    margin-top: -1.3em;
    background: var(--main-color);
    height: 2em;
    width: 2em;
    line-height: 2em;
    border: .3em solid #fff;
    text-align: center;
    font-weight: normal;
    border-radius: 2em;
    transition: all .3s ease-out;
    color: white;
}
section.cool-list > ol > li > em:hover, section.cool-list > ol > li > a:hover{
    background: #eee;
    font-weight: bolder;
}
/* Rotating effect */
/*
section.cool-list ol > li > em:hover:before,section.cool-list ol > li > a:hover:before{
    transform: rotate(360deg);
}*/
/* Lists inside lists */
section.cool-list > ol ol {
    margin: 0 0 0 2em; /* Add some left margin for inner lists */
    font-size: 75%;
    counter-reset: li2; /* Initiate a counter */
}
section.cool-list > ol ol > li > em:before,section.cool-list > ol ol > li > a:before{
    content: counter(li2);
    counter-increment: li2;
}
section.cool-list > ol > li > ul {
    list-style-type: disc;
    margin: 0 0 0 1em;
    font-size: 75%;
}
section.cool-list > ol ol > li > em {
    background: #efefef;
}

</style>

<!-- class: lead -->

# Repertório de Temas para Estudo do GT


<!-- _class: cool-list -->
1. *[**Deus**](1.deus.html)*
1. *[**Atributos de Deus**](2.atributos.html)*

> Última atualização: 25.nov.2021.