# 03_estruturas_dados_basicas.md

## 🎯 Objetivo
Aprender os fundamentos de manipulação de dados em programação, incluindo:
- tipos de dados
- variáveis
- estruturas de dados básicas (vetores e matrizes)
- entrada e saída de dados

Ao final, você será capaz de armazenar, manipular e exibir dados corretamente em um algoritmo.

---

## 📚 Conceitos-chave
- Tipos de dados
- Variáveis
- Atribuição
- Vetores (arrays)
- Matrizes
- Entrada de dados
- Saída de dados

---

## 🧠 Explicação

### 🔹 1. Tipos de dados
Tipos de dados definem o tipo de informação que uma variável pode armazenar.

Principais tipos:
- Inteiro → números inteiros (ex: 10, -5)
- Real → números com casas decimais (ex: 3.14)
- Caractere → um único símbolo (ex: 'A')
- String → conjunto de caracteres (ex: "Olá")
- Booleano → verdadeiro ou falso

---

### 🔹 2. Variáveis
Variáveis são espaços na memória usados para armazenar valores.

Exemplo:
idade = 20  
nome = "João"  

Regras:
- devem ter nome significativo  
- não podem começar com número  
- não usar espaços  

---

### 🔹 3. Atribuição
Atribuir significa guardar um valor na variável.

Exemplo:
x = 10  
y = x + 5  

Agora:
y = 15  

---

### 🔹 4. Entrada de dados
Permite que o usuário forneça informações ao programa.

Exemplo (pseudocódigo):
ler idade  

Exemplo (Python):
idade = int(input("Digite sua idade: "))  

---

### 🔹 5. Saída de dados
Permite exibir informações ao usuário.

Exemplo:
mostrar idade  

Exemplo (Python):
print(idade)  

---

### 🔹 6. Vetores (arrays)
Estrutura que armazena vários valores do mesmo tipo.

Exemplo:
vetor = [10, 20, 30, 40]

Acesso:
vetor[0] = 10  
vetor[1] = 20  

---

### 🔹 7. Percorrendo vetores

Exemplo:
para i de 0 até 3 faça  
    mostrar vetor[i]  
fimpara  

---

### 🔹 8. Matrizes
Estrutura bidimensional (linhas e colunas).

Exemplo:
matriz =  
[1, 2]  
[3, 4]  

Acesso:
matriz[0][0] = 1  
matriz[1][1] = 4  

---

### 🔹 9. Percorrendo matrizes

Exemplo:
para i de 0 até 1 faça  
    para j de 0 até 1 faça  
        mostrar matriz[i][j]  
    fimpara  
fimpara  

---

## 🔧 Ferramentas relacionadas
- Portugol Studio  
- Visualg  
- Python  
- C  
- Java  

---

## 💻 Exemplo prático

Exemplo 1 (entrada e saída):
nome = input("Digite seu nome: ")  
print("Olá", nome)  

---

Exemplo 2 (variáveis):
a = 5  
b = 10  
c = a + b  
print(c)  

---

Exemplo 3 (vetor):
numeros = [1, 2, 3, 4, 5]  
print(numeros[2])  

---

Exemplo 4 (loop em vetor):
numeros = [1, 2, 3, 4, 5]  

for i in range(5):  
    print(numeros[i])  

---

Exemplo 5 (matriz):
matriz = [[1, 2], [3, 4]]  

for i in range(2):  
    for j in range(2):  
        print(matriz[i][j])  

---

## ⚠️ Erros comuns

- Usar tipo de dado errado  
- Não inicializar variável  
- Acessar índice inexistente  
- Confundir posição do vetor (começa em 0)  
- Misturar tipos incompatíveis  
- Erro em matriz (linha x coluna)

---

## 📝 Resumo

- Tipos de dados definem o conteúdo  
- Variáveis armazenam valores  
- Entrada recebe dados  
- Saída exibe dados  
- Vetores armazenam múltiplos valores  
- Matrizes armazenam dados em duas dimensões  

Base essencial para qualquer programa.

---

## 📖 Referências

- CORMEN, T. H. et al. Algoritmos  
- GOODRICH, Michael T.; TAMASSIA, Roberto  
- ASCENCIO, A.F.G.; CAMPOS, E.A.V.  
- MANZANO, J.A.N.G; OLIVEIRA, J. F.  
- FORBELLONE, A.L.V.; EBERSPACHER, H. F.  

---

## 🚀 Desafio / Exercício

Exercício 1:  
Crie um programa que leia um número e mostre ele  

---

Exercício 2:  
Leia dois números e mostre a soma  

---

Exercício 3:  
Crie um vetor com 5 números e mostre todos  

---

Exercício 4:  
Crie uma matriz 2x2 e exiba os valores  

---

Exercício 5:  
Explique a diferença entre vetor e matriz  

---

## 🔚 Fim do módulo