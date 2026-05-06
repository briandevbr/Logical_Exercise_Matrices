# 🧮 Exercícios de Matrizes em Portugol

Este repositório contém exercícios práticos desenvolvidos em **Portugol** para treinar o uso de **matrizes**, estruturas de repetição, condicionais e análise de posições dentro de uma tabela de dados.

Uma matriz é uma estrutura bidimensional formada por **linhas** e **colunas**. Cada valor fica armazenado em uma posição específica, acessada por dois índices:

```txt
mat[linha, coluna]
```

Exemplo de matriz 3x3:

```txt
[1] [2] [3]
[4] [5] [6]
[7] [8] [9]
```

Esses exercícios ajudam a entender como percorrer uma matriz, preencher valores, exibir dados organizados e identificar regiões importantes, como diagonal principal, triângulo superior e triângulo inferior.

---

## 📌 Conteúdos praticados

- Criação e preenchimento de matrizes
- Leitura de valores digitados pelo usuário
- Exibição da matriz na tela
- Identificação de números pares e ímpares
- Criação de matriz identidade
- Soma da diagonal principal
- Produto de uma linha específica
- Verificação do maior valor de uma coluna
- Separação entre diagonal, triângulo superior e triângulo inferior

---

## 📁 Exercícios

### 🔹 Exercício 1 — Matriz 3x3

Trabalha com uma matriz de ordem 3, permitindo preencher valores, exibir a matriz completa e identificar quais números são pares e ímpares.

**Principais conceitos:**

- Matriz 3x3
- Laços aninhados
- Verificação com `mod`
- Separação entre pares e ímpares

---

### 🔹 Exercício 2 — Matriz Identidade 5x5

Cria uma matriz identidade de ordem 5, preenchendo a diagonal principal com `1` e as demais posições com `0`.

Exemplo:

```txt
1 0 0 0 0
0 1 0 0 0
0 0 1 0 0
0 0 0 1 0
0 0 0 0 1
```

**Lógica principal:**

```txt
se linha = coluna → recebe 1
caso contrário → recebe 0
```

---

### 🔹 Exercício 3 — Análise de Matriz 5x5

Realiza análises em uma matriz 5x5, como soma da diagonal principal, produto da segunda linha e identificação do maior valor da terceira coluna.

**Principais conceitos:**

- Diagonal principal
- Linha específica
- Coluna específica
- Comparação de valores
- Acúmulo de soma e produto

---

### 🔹 Exercício 4 — Regiões da Matriz

Mostra visualmente partes específicas de uma matriz, como diagonal principal, triângulo superior e triângulo inferior.

**Regras principais:**

```txt
linha = coluna → diagonal principal
linha < coluna → triângulo superior
linha > coluna → triângulo inferior
```

---

## 🧠 Resumo da lógica das matrizes

Para trabalhar com matrizes, normalmente usamos dois laços de repetição:

```portugol
para l de 1 ate 5 faca
   para c de 1 ate 5 faca
      escreva(mat[l,c])
   fimpara
fimpara
```

O primeiro laço controla as **linhas** e o segundo controla as **colunas**.  
Essa estrutura permite acessar cada posição da matriz individualmente.

---

## ⚙️ Tecnologias utilizadas

- Portugol
- Visualg
- Lógica de programação
- Matrizes
- Estruturas de repetição
- Estruturas condicionais

---

## 🚀 Como executar

1. Abra o Visualg.
2. Carregue um dos arquivos `.ALG`.
3. Execute o algoritmo.
4. Digite os valores solicitados.
5. Observe os resultados exibidos na tela.

---

## 📚 Objetivo do projeto

O objetivo deste repositório é reforçar a base de **lógica de programação com matrizes**, entendendo como os dados são organizados em linhas e colunas e como é possível analisá-los usando condições e repetições.

Esses exercícios servem como prática para desenvolver raciocínio lógico e preparar a base para estruturas mais avançadas em programação.
