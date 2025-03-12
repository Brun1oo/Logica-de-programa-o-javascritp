# Variáveis 

Os dados de um programa são armazenados em variáveis. As variáveis são ferramentas indispensáveis na programação, são nelas que colocamos valores para podermos trabalhar com 
esses dados posteriormente.

No javaScript, podemos declarar variáveis de três maneiras 
- Usando a palavra reservada var 
- Usando a palavra reservada ler 
- Usando a palavra reservada const

---

**Var:** <br>
A instruçao var declara uma variável no escopo de uma função ou no escopo global e é opcional inicializar o seu valor.

![Captura de tela 2025-03-12 163029](https://github.com/user-attachments/assets/6b351f18-5c94-4fe5-8916-d4736ab5ded5)

---

**Let:** <br>
Variáveis definidas com let não podem ser redeclaradas, ou seja, você não pode declarar novamente uma variável com o mesmo nome.

![Captura de tela 2025-03-12 163115](https://github.com/user-attachments/assets/65d44914-e3c2-4be4-a67e-bcab59d2e824)
![Captura de tela 2025-03-12 163209](https://github.com/user-attachments/assets/182c72fd-81ea-4788-89ff-e9d651c6990c)

---

**Const:** <br>
Variáveis definidas com const não podem ser redeclaradas e não podem ter seu valor alterado, ou seja, você não pode declarar novamente uma variável com o mesmo nome e uma 
vez inicializada o seu valor será o mesmo até o fim do programa.

![Captura de tela 2025-03-12 163308](https://github.com/user-attachments/assets/4645cf14-0f63-4e04-8346-54fdc537d136)

---

## Valores e tipos de dados 

**Números:** <br>
O JavaScript tem um único tipo de número. Internamente, é representado como ponto flutuante de 64 bits, o mesmo que o double do Java. Portando, em JS, não há diferença entre 
1 e 1.0, esses números são interpretados como mesmo valor.

**Strings:** <br>
Strings são sequência de caracteres, que no JavaScript, devem ser envolvidas utilizando aspas simples ou aspas duplas, mesmo se elas contêm zero ou mais caracteres

![Captura de tela 2025-03-12 164130](https://github.com/user-attachments/assets/6322ecd5-8aa8-49c4-9b16-12afbca0782d)

**Números especiais:** <br>
Existem três valores especiais em JS que são considerados números, mas não se comportam como números normais. Os dois primeiros são Infinity e -Infinity, que representam os 
infinitos positivos e negativos. A expressão Infinity - 1 ainda é infinito e assim por diante. O terceiro é o NaN significa “Not a Number”

---

## Escopo de Variáveis

O escopo é o conjunto de regras que determinam o uso e a validade de variáveis nas diversas partes do programa. Um escopo define uma região do programa definida pela abertura
e fechamento de chaves { }. JavaScript permite criar variáveis em três escopos: global, de função e de bloco. O escopo de função e de bloco também são chamados de escopo 
local. Nesse caso, o escopo de uma variável define uma região do código onde a variável é visível, ou seja, ela pode ser acessada. Já o escopo global fica visível para todas 
as partes de nosso código.

![Captura de tela 2025-03-12 164746](https://github.com/user-attachments/assets/066c46e6-f9f7-4bfe-a638-363ff2202f29)

---

## Operadores de comparação

![Captura de tela 2025-03-12 165009](https://github.com/user-attachments/assets/18a0652c-0f4f-4b33-8cda-1dda8f572cf6)

## Operadores lógicos 

Operadores lógicos são usados em programação para concatenar expressões que estabelecem uma relação de comparação entre valores. Os principais operadores lógicos são 
mostrados abaixo: 

![Captura de tela 2025-03-12 165056](https://github.com/user-attachments/assets/4dc71ac0-3536-4fe6-8815-d47a3cd5207e)

## Operadores de atribuição

O operador de atribuição permite atribuir um valor a uma variável, por exemplo. O JavaScript permite utilizar uma forma contraída do operador de atribuição. A tabela a 
seguir, mostra diversos exemplos do operador de atribuição com os operadores

![Captura de tela 2025-03-12 165159](https://github.com/user-attachments/assets/61cc900e-eb53-4132-9c98-0264d3df6049)
