# Javascript

O JavaScript é “A” linguagem de script para front end web.

### Visão geral da linguagem:
- Multiparadigma (imperativo, oo, funcional)
- Interpretada
- Sintaxe básica baseada em C
- Case sensitive
- Tipagem dinâmica
- Funções de primeira ordem
- Arrays heterogêneos
- Flexível e expressiva
- Padrão de mercado para script front end (client-side)
- Também usada para back end e desktop


**Tipos de dados:**
- **number**
- **string**
- **boolean**
- **object**
- **array (object)**
- **null (object)**
- **undefined**

```javascript
const a = 10
const b = 10.5
const c = 'Maria'
const d = 'a'
const e = false
const f = {name: 'Maria', age: 25}
const g = ['a', 15, false, 'maria']
const h = null
const i = undefined

console.log(typeof a)
console.log(typeof b)
console.log(typeof c)
console.log(typeof d)
console.log(typeof e)
console.log(typeof f)
console.log(typeof g)
console.log(typeof h)
console.log(typeof i)
```

**Saìda:**
```javascript
console.log(typeof a)
```
O operador **typeof** returna uma string indicando o tipo da variavel.

**Declarando o javascript dentro do projeto:**
```javascript

// conteúdo dentro de arquivo .js:
console.log(typeof a)

// Declaração dentro do projeto .html
<body>
   <script src="./script.js"></script> 
</body>
```
**Comentário de uma linha:**
```c
//console.log("Uma String literal pode ficar entre aspas duplas.");
```

**Comentário de múltiplas linhas:**
```c
/*
console.log('Uma String literal pode ficar entre aspas simples.');
console.log(`Uma String literal pode ficar entre crases.`);
*/
```

**String com aspas duplas:**
```c
console.log("Uma String literal pode ficar entre aspas duplas.");
```

**String com aspas simples:**
```c
console.log('Uma String literal pode ficar entre aspas simples.');
```

**String com crases:**
```c
console.log(`Uma String literal pode ficar entre crases.`);
```
**Concatenação:**
```c
const num = 14.5;
console.log("Concatenação: " + num);
```

**Interpolação:**
```c
const num = 14.5;
console.log(`interpolação: ${num}`);
```

**Converter número para String:**
```c
const num = 14.5;
const converterNumber = num.toString();
console.log(`O tipo de ${converterNumber} é ${typeof converterNumber}`);
```

**Fixar casas decimais:**
```c
const fixNumber = num.toFixed(2);
console.log(`O tipo de ${fixNumber} é ${typeof fixNumber}`);
```

**Converter String em número:**
```c
const converterString = Number("15.5");
console.log(`O tipo de ${converterString} é ${typeof converterString}`);
```

**Converter string para int com casa decimal 10:**
```c
const converterNumber10 = parseInt("15", 10);
console.log(`O tipo de ${converterNumber10} é ${typeof converterNumber10}`);
```

**Converter número flutuante para inteiro:**
```c
const convertFloat = parseFloat("19.5");
console.log(`O tipo de ${convertFloat} é ${typeof convertFloat}`);
```

**Texto minúsculo:**
```c
const lawerCase = "Flávio";
console.log(`${lawerCase.toLowerCase()}`);
```

**Texto maiúsculo:**
```c
const upperCase = "Flávio";
console.log(`${upperCase.toUpperCase()}`);
```

**Recuperar letra específica:**
```c
const letter = "Flávio Júnior";
console.log(`${letter.charAt(2)}`);
```

**Recuperar letra específica com colchetes:**
console.log(`${letter[2]}`);

**Subistituir letra:**
```c
console.log(`${letter.replace("á", "a")}`);
```

**Subistituir todas as letras:**
```c
console.log(`${letter.replace(/o/g, "os")}`);
```

**Ver tamanho da letra:**
```
console.log(`${letter.length}`);
```

**Retornar primeira posição da letra:**
```c
console.log(`${letter.indexOf("o")}`);
```

**Retornar última posição da letra:**
```c
console.log(`${letter.lastIndexOf("o")}`);
```

**Recortar letra:**
```c
const data = "02/11/2024";
console.log(`${data.substring(3, 5)}`);
```

**Remover espaço em branco:**
```c
const blackSpace = "Flávio Júnior   ";
console.log(`${blackSpace.trim()}`);
```

**Operadores:**
```c
const valueOne = 15;
const valueTwo = 3;

console.log(`soma ${valueOne + valueTwo}`);
console.log(`subtração ${valueOne - valueTwo}`);
console.log(`multiplicação ${valueOne * valueTwo}`);
console.log(`divisão ${valueOne / valueTwo}`);
console.log(`resto ${valueOne % valueTwo}`);
```

**Comparadores:**
```c
console.log(`Menor q ${valueOne < valueTwo}`);
console.log(`Maior q ${valueOne > valueTwo}`);
console.log(`Menor ou igual ${valueOne <= valueTwo}`);
console.log(`Igual ou maior ${valueOne >= valueTwo}`);
```

**Converte para um tipo em comum, depois compara:**
- == 
- !=

**Compara levando em conta também o tipo:**
- === 
- !== 

**Operadores comparativos de igualdade:**
```c
console.log(`"" == false: ${"" == false}`);
console.log(`"" === false: ${"" === false}`);
console.log(`"17" == 17: ${"17" == 17}`);
console.log(`"17" === 17: ${"17" === 17}`);
```

**Operadores lógicos:**
- && (E)
- || (OU)
- ! (NÃO)

**Operadores lógicos:**
```c
console.log(`(10 > 5) && (10 > 20): ${(10 > 5) && (10 > 20)}`);
console.log(`(10 > 5) && (10 < 20): ${(10 > 5) && (10 < 20)}`);
console.log(`(10 > 5) || (10 > 20): ${(10 > 5) || (10 > 20)}`);
console.log(`(10 < 5) || (10 > 20): ${(10 > 5) && (10 > 20)}`);
console.log(`!(10 > 5): ${!(10 > 5)}`);
```
