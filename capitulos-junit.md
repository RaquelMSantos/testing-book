---
permalink: /capitulos-junit/
title: Capítulos
---

# JUnit

O JUnit nada mais é que um framework que facilita o desenvolvimento e execução de testes de unidade em código Java. Atualmente o core deste framework está dividido em sete classes e interfaces, são elas: Assert, TestResult, Test, TestListener, TestCase, TestSuite e BaseTestRunner.

## O que é o JUnit 

[![O que é o JUnit](http://img.youtube.com/vi/P-m1IrWwHOo/0.jpg)](http://www.youtube.com/watch?v=P-m1IrWwHOo "O que é o JUnit")

## Método de comparação – assertEquals()

O método assertEquals (que será exemplificado neste tutorial) é um método que pode ser implementado de várias formas diferentes. Ele recebe como parâmetro o resultado do método que está sendo testado e o resultado esperado pelo desenvolvedor caso o método testado esteja correto. O tipo desses valores passados como parâmetro pode ser vários (int, double, String, etc…).

## Métodos setUp() e tearDown()

O método setUp() é utilizado para sinalizar o início do processo de teste. Vem antes do método de teste. O método tearDown() sinaliza o final do processo, desfazendo o que o setUp() fez. Vem depois do método de Teste.
