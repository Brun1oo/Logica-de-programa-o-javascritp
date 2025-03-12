## Desvios condicionais

Os desvios condicionais decidem o fluxo de execução de programa. Esses desvios são construídos com estruturas condicionais 
simples (if), composta (if-else) e switch. Uma das tarefas fundamentais de qualquer programa é decidir o que deve ser executad
o a seguir.

Se a condição entre parênteses for verdadeira, o conjunto de instruções entre chaves (dentro do bloco da estrutura condicional
if) será executado, caso contrário esse conjunto é saltado e o programa irá executar a próxima instrução fora das chaves da 
estrutura if.

```JavaScript
let num1 = 15;
let num2 = 5;

if (num1 > num2) {
   console.log(`O número ${num1} é maior que ${num2}`)
} else {
   console.log(`O número ${num2} é maior que ${num1}`)
}

```

### Desvios condicionais encadeados

Você pode encadear vários desvios condicionais quando for necessário verificar diversas condições. E cada condição depende do 
resultado da condição anterior. Basicamente, if dentro de if (denominado ifs-elses aninhados)

```JavaScript
let num1 = 15;
let num2 = 5;

if (num1 > num2) {
   console.log(`O número ${num1} é maior que ${num2}`)
} else if (num1 == num2){
   console.log(`O número ${num2} é igual a ${num1}`)
}else {
   console.log(`O número ${num2} é maior que ${num1}`)
}

```

### Operador ternário

O operador ternário é uma instrução equivalente a estrutura condicional composta if…else e a sua vantagem é tornar o código bem
mais enxuto. A sua sintaxe é:

```JavaScript
let clima = `sol`
let res = clima == `sol`? `Irei à praia`: `Nãp irei à praia`
console.log(res)
```

---

## Coerção de tipo

Nem todos os operadores são símbolos. Alguns são escritos como palavras. Um exemplo é o operador typeof, que produz um valor
de string nomeando o tipo do valor que você forneceu.

![Captura de tela 2025-03-12 171054](https://github.com/user-attachments/assets/9a30ba9a-8065-4878-a240-cac165ad17a9)

JavaScript faz de tudo para aceitar quase qualquer programa que você forneça, até mesmo programas que fazem coisas estranhas.
Por exemplo, você pode fazer operações com tipos diferentes de dados:

![Captura de tela 2025-03-12 171140](https://github.com/user-attachments/assets/20ca3edd-89da-4c11-a06a-f167f57eecfc)

--- 

## Métodos de strings

Os métodos de strings são funções embutidas em linguagens de programação que permitem manipular e processar textos de forma 
eficiente. Cada linguagem possui seus próprios métodos, mas a ideia geral é a mesma.

**Tamanho da string:** <br>
O length (ou comprimento) de uma string se refere à quantidade de caracteres que ela possui, incluindo letras, números, espaços
e símbolos. 

```JavaScript
let texto = "Olá, mundo!";
console.log(texto.length);  // Saída: 12
```

**Maiúsculas e minúsculas:** <br>
Você pode transformar todos os caracteres de uma string para maiúsculo ou para minúsculo, isso facilitam, por exemplo, comparar 
strings para verificar se são iguais.

```JavaScript
let texto = "Olá, mundo!";
console.log(texto.toUpperCase());  
// Saída: "OLÁ, MUNDO!"
```

```JavaScript
let texto = "Olá, MUNDO!";
console.log(texto.toLowerCase());  
// Saída: "olá, mundo!"
```

**Substituir uma string dentro da string:** <br>
O método replace substitui um pedaço específico da string por outra coisa que você desejar.

```JavaScript
let frase = "Eu amo Python!";
let novaFrase = frase.replace("Python", "JavaScript");
console.log(novaFrase);  
// Saída: "Eu amo JavaScript!"
```


