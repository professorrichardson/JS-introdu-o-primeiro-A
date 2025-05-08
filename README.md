**Resumo: Primeiros Passos com JavaScript (VS Code + Node.js)**

----------

**1. Variáveis**

```javascript
let nome = "Lucas";
const idade = 18;

```

-   `let`: cria uma variável que pode mudar
    
-   `const`: cria uma variável que não muda
    

----------

**2. Mostrar no terminal (console.log)**

```javascript
console.log("Texto ou variável");

```

Exemplo:

```javascript
console.log("Olá, mundo!");

```

----------

**3. Operadores**

```javascript
+   Soma
-   Subtração
*   Multiplicação
/   Divisão

```

Exemplo:

```javascript
let resultado = 5 + 3;
console.log(resultado); // Mostra 8

```

----------

**4. Condicional (if / else)**

```javascript
if (condicao) {
  // Faz isso
} else {
  // Ou faz isso
}

```

Exemplo:

```javascript
let idade = 20;
if (idade >= 18) {
  console.log("Maior de idade");
} else {
  console.log("Menor de idade");
}

```

----------

**5. Repetição (for)**

```javascript
for (let i = 1; i <= 5; i++) {
  console.log(i);
}

```

-   Repete de 1 a 5
    

----------

**6. Lista (Array)**

```javascript
let frutas = ["maçã", "banana", "uva"];

```

Percorrer lista:

```javascript
for (let i = 0; i < frutas.length; i++) {
  console.log(frutas[i]);
}

```

----------

**Dicas**

-   Use nomes simples para variáveis
    
-   Sempre termine as linhas com `;`
    
-   Salve o arquivo como `.js`
    
-   Rode no terminal: `node arquivo.js`
    

----------

**Comandos importantes do terminal**

-   `node arquivo.js` → Roda o código
    
-   `clear` → Limpa o terminal
    
-   `code .` → Abre a pasta no VS Code
    

----------

**Bons códigos! :)**
