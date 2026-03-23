# 02_logica_algoritmos.md

## 🎯 Objetivo
Aprender os fundamentos da lógica de programação e construção de algoritmos, incluindo:
- estruturas sequenciais, condicionais e de repetição
- operadores lógicos
- construção passo a passo de algoritmos
- representação por fluxogramas

Ao final, você será capaz de criar algoritmos corretos e entender seu fluxo de execução.

---

## 📚 Conceitos-chave
- Algoritmo
- Lógica sequencial
- Estrutura condicional (if/else)
- Estrutura de repetição (for/while)
- Operadores lógicos (AND, OR, NOT)
- Fluxogramas
- Pseudocódigo

---

## 🧠 Explicação

### 🔹 1. O que é um algoritmo?
Um algoritmo é uma sequência finita de passos para resolver um problema.

Exemplo simples:
1. Ler dois números  
2. Somar os números  
3. Mostrar o resultado  

---

### 🔹 2. Lógica sequencial
Execução linear, passo a passo, sem desvios.

Exemplo:
ler A  
ler B  
C = A + B  
mostrar C  

---

### 🔹 3. Estrutura condicional

Permite tomar decisões com base em condições.

Forma geral:
se (condição) então  
    ação  
senão  
    outra ação  
fimse  

Exemplo:
se (idade >= 18) então  
    mostrar "Maior de idade"  
senão  
    mostrar "Menor de idade"  
fimse  

---

### 🔹 4. Operadores lógicos

AND → E (todas condições verdadeiras)  
OR → OU (pelo menos uma verdadeira)  
NOT → NÃO (inverte valor lógico)

Exemplo:
se (idade >= 18 AND temCNH = verdadeiro) então  
    mostrar "Pode dirigir"  
fimse  

---

### 🔹 5. Estruturas de repetição

Permitem executar várias vezes um bloco de código.

WHILE (enquanto condição for verdadeira):
contador = 1  
enquanto (contador <= 5) faça  
    mostrar contador  
    contador = contador + 1  
fimenquanto  

FOR (controle por variável):
para i de 1 até 5 faça  
    mostrar i  
fimpara  

---

### 🔹 6. Construção de algoritmos

Passos:
1. Entender o problema  
2. Definir entradas  
3. Definir processamento  
4. Definir saídas  

---

### 🔹 7. Fluxogramas

Representação gráfica do algoritmo.

Símbolos principais:
- Início/Fim → oval  
- Processo → retângulo  
- Decisão → losango  
- Entrada/Saída → paralelogramo  

Exemplo textual:
Início  
↓  
Ler número  
↓  
Número > 10?  
↓       ↓  
Sim     Não  
↓        ↓  
Mostrar A  Mostrar B  
↓  
Fim  

---

## 🔧 Ferramentas relacionadas
- Portugol Studio  
- Visualg  
- Flowgorithm  
- Draw.io  
- Lucidchart  

---

## 💻 Exemplo prático

Exemplo 1 (pseudocódigo):
inicio  
    ler numero  
    se (numero % 2 == 0) então  
        mostrar "Par"  
    senão  
        mostrar "Ímpar"  
    fimse  
fim  

---

Exemplo 2 (Python):
numero = int(input("Digite um número: "))  
if numero % 2 == 0:  
    print("Par")  
else:  
    print("Ímpar")  

---

Exemplo 3 (repetição):
for i in range(1, 6):  
    print(i)  

---

Exemplo 4 (operadores lógicos):
idade = 20  
tem_cnh = True  

if idade >= 18 and tem_cnh:  
    print("Pode dirigir")  

---

## ⚠️ Erros comuns

- Não seguir a ordem lógica correta  
- Condições mal definidas  
- Loop infinito  
- Variáveis não inicializadas  
- Confundir AND com OR  
- Não testar o algoritmo  

---

## 📝 Resumo

- Algoritmo = sequência de passos  
- Sequencial → execução linear  
- Condicional → decisão  
- Repetição → execução múltipla  
- Operadores lógicos → combinam condições  
- Fluxogramas → visão gráfica  

Base essencial da programação.

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
Criar algoritmo que leia um número e informe se é positivo ou negativo  

---

Exercício 2:  
Criar algoritmo que leia três números e mostre o maior  

---

Exercício 3:  
Exibir números de 1 a 10 usando repetição  

---

Exercício 4:  
Criar condição usando AND e OR  

---

Exercício 5:  
Explique a diferença entre estrutura condicional e repetição  

---

## 🔚 Fim do módulo