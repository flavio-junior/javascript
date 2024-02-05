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
