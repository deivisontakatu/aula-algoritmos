# 05_testes_validacao_algoritmos.md

## 🎯 Objetivo
Aprender a validar algoritmos e garantir que funcionem corretamente, por meio de:
- testes de mesa passo a passo
- identificação de erros lógicos
- rastreamento de execução
- criação de casos de teste (entrada/saída)
- noções básicas de validação sistemática

Ao final, você será capaz de analisar algoritmos e detectar erros antes da execução real.

---

## 📚 Conceitos-chave
- Teste de mesa
- Validação de algoritmos
- Erro lógico
- Rastreamento de execução
- Caso de teste
- Entrada e saída esperada
- Verificação de resultados

---

## 🧠 Explicação

### 🔹 1. Validação de algoritmos
Validar um algoritmo significa garantir que ele resolve corretamente o problema proposto.

Isso envolve:
- testar diferentes entradas  
- verificar resultados  
- analisar o comportamento  

---

### 🔹 2. Teste de mesa (passo a passo)

É a execução manual do algoritmo, linha por linha.

Exemplo:

Algoritmo:
x = 1  
y = 2  
z = x + y  

Tabela:

Passo | x | y | z  
1     | 1 | - | -  
2     | 1 | 2 | -  
3     | 1 | 2 | 3  

---

### 🔹 3. Rastreamento de execução

Consiste em acompanhar a execução do algoritmo, observando mudanças nas variáveis.

Exemplo:

contador = 1  

enquanto (contador <= 3) faça  
    mostrar contador  
    contador = contador + 1  
fimenquanto  

Rastreamento:

Iteração | contador  
1        | 1  
2        | 2  
3        | 3  

---

### 🔹 4. Identificação de erros lógicos

Erro lógico ocorre quando:
- o algoritmo executa  
- mas o resultado está errado  

Exemplo:

Erro:
media = nota1 + nota2 / 2  

Correto:
media = (nota1 + nota2) / 2  

👉 Falta de parênteses altera o resultado

---

### 🔹 5. Casos de teste

Um caso de teste é composto por:
- entrada  
- processamento esperado  
- saída esperada  

Exemplo:

Entrada: 2, 3  
Processo: soma  
Saída esperada: 5  

---

### 🔹 6. Tipos de casos de teste

- Caso normal → valores comuns  
- Caso limite → extremos (0, negativo, máximo)  
- Caso inválido → entradas erradas  

Exemplo:

Entrada | Saída esperada  
5       | positivo  
0       | neutro  
-3      | negativo  

---

### 🔹 7. Estratégia de validação

Passos:
1. Criar algoritmo  
2. Fazer teste de mesa  
3. Criar casos de teste  
4. Testar diferentes cenários  
5. Corrigir erros encontrados  

---

## 🔧 Ferramentas relacionadas
- Papel e caneta (teste de mesa)  
- Planilhas (Excel)  
- Portugol Studio  
- Visualg  
- Python (execução prática)  

---

## 💻 Exemplo prático

Exemplo 1 (teste de mesa):

Algoritmo:
a = 2  
b = 3  
c = a * b  

Tabela:
Passo | a | b | c  
1     | 2 | - | -  
2     | 2 | 3 | -  
3     | 2 | 3 | 6  

---

Exemplo 2 (erro lógico):

Código:
resultado = 10 - 2 * 3  

Resultado real: 4  
Possível erro esperado: 24  

👉 problema de precedência  

---

Exemplo 3 (caso de teste):

Problema: verificar par ou ímpar  

Entrada | Saída esperada  
2       | par  
3       | ímpar  
0       | par  

---

Exemplo 4 (rastreamento):

i = 1  

enquanto (i <= 3) faça  
    i = i + 1  
fimenquanto  

Valores:
1 → 2 → 3 → 4  

---

## ⚠️ Erros comuns

- Não testar o algoritmo antes de implementar  
- Testar apenas um caso  
- Ignorar casos extremos  
- Não rastrear variáveis  
- Confundir erro lógico com erro de sintaxe  
- Não validar entrada de dados  

---

## 📝 Resumo

- Teste de mesa = simulação manual  
- Rastreamento = acompanhar variáveis  
- Erro lógico = resultado errado com execução correta  
- Casos de teste = entradas + saídas esperadas  
- Validação = garantir funcionamento correto  

Essencial para provas e desenvolvimento correto.

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
Faça o teste de mesa do algoritmo:  
x = 5  
y = x * 2  
z = y - 3  

---

Exercício 2:  
Identifique o erro lógico:  
media = nota1 + nota2 / 2  

---

Exercício 3:  
Crie 3 casos de teste para um algoritmo de soma  

---

Exercício 4:  
Faça o rastreamento de um loop simples  

---

Exercício 5:  
Explique a diferença entre teste de mesa e execução real  

---

## 🔚 Fim do módulo