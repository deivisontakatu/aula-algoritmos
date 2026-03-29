# 04_funcoes_boas_praticas.md

## 🎯 Objetivo
Aprender a organizar melhor programas utilizando:
- funções (sub-rotinas)
- testes de mesa
- testes unitários
- boas práticas de codificação (indentação, legibilidade e comentários)

Ao final, você será capaz de escrever códigos mais organizados, testáveis e fáceis de entender.

---

## 📚 Conceitos-chave
- Funções
- Sub-rotinas
- Parâmetros
- Retorno
- Teste de mesa
- Teste unitário
- Indentação
- Legibilidade
- Comentários

---

## 🧠 Explicação

### 🔹 1. Funções (sub-rotinas)
Funções são blocos de código reutilizáveis que executam uma tarefa específica.

Vantagens:
- reutilização de código  
- organização  
- facilidade de manutenção  

Exemplo:
função soma(a, b)  
    retorno a + b  
fimfunção  

---

### 🔹 2. Parâmetros e retorno

Parâmetros → valores de entrada  
Retorno → valor devolvido pela função  

Exemplo:
função quadrado(x)  
    retorno x * x  
fimfunção  

---

### 🔹 3. Uso de funções

Exemplo:
resultado = soma(5, 3)  
mostrar resultado  

---

### 🔹 4. Teste de mesa
É a simulação manual da execução de um algoritmo.

Serve para:
- entender o fluxo  
- identificar erros lógicos  
- validar resultados  

Exemplo:

Algoritmo:
x = 2  
y = x + 3  

Tabela:
Passo | x | y  
1     | 2 | -  
2     | 2 | 5  

---

### 🔹 5. Testes unitários
Testes feitos em partes específicas do código (funções).

Objetivo:
- garantir que cada função funciona corretamente  

Exemplo:
entrada: soma(2, 3)  
saída esperada: 5  

---

### 🔹 6. Indentação
Organização visual do código.

Exemplo correto:
se (idade >= 18) então  
    mostrar "Maior"  
fimse  

Exemplo errado:
se (idade >= 18) então  
mostrar "Maior"  
fimse  

---

### 🔹 7. Legibilidade
Código deve ser fácil de ler.

Boas práticas:
- nomes claros (ex: total, idade)  
- evitar abreviações confusas  
- organizar o código  

---

### 🔹 8. Comentários
Explicam o código.

Exemplo:
# calcula a soma de dois números  
soma = a + b  

---

## 🔧 Ferramentas relacionadas
- Visual Studio Code  
- PyCharm  
- JUnit  
- PyTest  
- Portugol Studio  

---

## 💻 Exemplo prático

Exemplo 1 (função em Python):
def soma(a, b):  
    return a + b  

print(soma(5, 3))  

---

Exemplo 2 (função com retorno):
def quadrado(x):  
    return x * x  

print(quadrado(4))  

---

Exemplo 3 (teste unitário simples):
def soma(a, b):  
    return a + b  

resultado = soma(2, 3)  

if resultado == 5:  
    print("Teste OK")  
else:  
    print("Erro")  

---

Exemplo 4 (comentários e legibilidade):
# calcula média  
nota1 = 7  
nota2 = 8  
media = (nota1 + nota2) / 2  

print(media)  

---

## ⚠️ Erros comuns

- Criar funções muito grandes  
- Não usar funções (código repetido)  
- Falta de indentação  
- Nomes de variáveis confusos  
- Não testar o código  
- Comentários desnecessários ou inexistentes  

---

## 📝 Resumo

- Funções organizam o código  
- Parâmetros recebem dados  
- Retorno devolve resultado  
- Teste de mesa valida lógica  
- Teste unitário valida partes  
- Indentação melhora leitura  
- Comentários explicam o código  

Código limpo = mais fácil de entender e manter.

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
Crie uma função que receba dois números e retorne a soma  

---

Exercício 2:  
Crie uma função que calcule o dobro de um número  

---

Exercício 3:  
Faça um teste de mesa para um algoritmo simples  

---

Exercício 4:  
Crie um teste unitário para uma função  

---

Exercício 5:  
Melhore a legibilidade de um código desorganizado  

---

## 🔚 Fim do módulo