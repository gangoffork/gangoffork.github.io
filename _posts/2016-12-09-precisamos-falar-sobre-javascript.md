---
layout: post
title:  "Precisamos falar sobre JavaScript."
date:   2016-12-07 14:32:45
description:  Hoje falamos sobre JavaScript e suas características.
categories:
  - blog
author: Francisco Marinho
---

JavaScript é uma linguagem multi-paradigma, de função de primeira classe, orientada a objeto. Quase tudo é um objeto, com exceção de seus tipos primitivos. Sim ela tem tipos, e também é de tipagem dinâmica e fraca, e de conversão implícita, dentre outras características.
A intenção desse post não é trazer uma abordagem profunda dessas características e sim dar uma visão ampla e resumida. Bem como fornecer um conhecimento básico para minimizar alguns dos problemas com javaScript

###### Linguagem multi-paradigma
JavaScript suporta mais de um paradigma de programação, os mais conhecidos são orientação a objeto, e funcional.

###### Higher-order function
São funções que operam em outras funções. Recebem uma ou mais funções como argumentos, e ou retornam uma função como resultado.

###### Orientada a objetos

###### Tipos em javascript
JavaScript define 7 tipos nativos: null; undefined; boolean; number; string; object; symbol.


###### Dinâmica e fracamente tipada
Ser dinamicamente tipada significa que o desenvolvedor não precisa informar o tipo da variável, na hora de instância-la o interpretador irá colocar o tipo mais apropriado para o valor atribuído à variável. Fracamente tipada quer dizer que a variável pode receber outro tipo sem a necessidade de cast. Nesse caso JavaScript irá usar um conjunto de regras para fazer essas conversões.
Essas características tornam JavaScript muito flexível, mas por outro lado, pode causar alguns problemas, se um operador for usado de maneira incorreta, as coisas podem sair um pouco estranhas. JavaScript tem suas próprias regras de conversão e algumas delas podem ser um pouco diferente do que você está acostumado.

###### Conversão implícita
