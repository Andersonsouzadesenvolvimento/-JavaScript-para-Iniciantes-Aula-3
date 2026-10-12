# -JavaScript-para-Iniciantes-Aula-3



# 🚀 JavaScript para Iniciantes — Aula 3

## 🔁 1. Evitando repetições — DRY

DRY significa **Don't Repeat Yourself** (Não se repita).

Esse princípio ajuda a escrever códigos mais organizados, reutilizáveis e fáceis de manter.

### Exemplo prático

```javascript
var preco = 20;
var totalComprado = 5;
var precoTotal = preco * totalComprado;

console.log(precoTotal); // 100
```

**Entendendo o código:**

- `preco`: valor de cada produto.
- `totalComprado`: quantidade de produtos.
- `precoTotal`: resultado da multiplicação.

Em vez de repetir os valores manualmente, utilizamos variáveis para reaproveitar as informações.

## 🧠 2. Sintaxe das variáveis

A sintaxe é a forma correta de escrever um comando na linguagem de programação.

Com `var`, declaramos uma variável utilizando uma palavra-chave, um nome, o sinal de igual e o valor atribuído.

### Exemplo

```javascript
var nome = 'André';
var idade = 28;
var possuiFaculdade = true;
```

Observe os tipos de dados:

- `'André'`: texto (*string*).
- `28`: número (*number*).
- `true`: valor lógico (*boolean*).

## 📝 3. Declarando várias variáveis com vírgula

Também é possível declarar várias variáveis usando uma única palavra-chave `var`, separando as declarações por vírgulas.

```javascript
var nome = 'André',
    idade = 28,
    possuiFaculdade = true;

console.log(nome);
console.log(idade);
console.log(possuiFaculdade);
```

Essa forma funciona, mas escrever cada declaração em uma linha costuma facilitar a leitura para quem está começando.

## 🎯 4. Desafio prático

Crie um pequeno programa que calcule o preço total de uma compra.

**Requisitos:**

1. Declare uma variável com o preço de um produto.
2. Declare outra com a quantidade comprada.
3. Calcule o valor total.
4. Exiba o resultado usando `console.log()`.

### Solução de exemplo

```javascript
var preco = 15;
var quantidade = 4;
var total = preco * quantidade;

console.log('Total da compra: R$', total);
```

Resultado esperado: `Total da compra: R$ 60`

## ✅ Resumo da aula

- O princípio DRY evita repetições desnecessárias.
- A sintaxe define como escrever corretamente o código.
- Podemos declarar várias variáveis usando vírgulas.
- `console.log()` permite visualizar os resultados no console.

---

💻 Mais uma etapa concluída na minha jornada de aprendizado em JavaScript!

#JavaScript #Programação #DesenvolvimentoWeb #EstudosDeProgramação #DRY
