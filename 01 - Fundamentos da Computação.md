# 01_fundamentos_computacao.md

## 🎯 Objetivo
Compreender os fundamentos da computação, incluindo:
- funcionamento básico do hardware
- representação de dados em binário
- estrutura de sistemas computacionais
- noções de compiladores

Ao final, você será capaz de entender como um programa é executado desde o código até o hardware.

---

## 📚 Conceitos-chave
- Hardware vs Software
- CPU (Unidade Central de Processamento)
- Memória (RAM e armazenamento)
- Barramentos (dados, endereço e controle)
- Ciclo de instrução
- Representação binária
- Sistemas de numeração (binário, decimal, hexadecimal)
- Compiladores e interpretadores

---

## 🧠 Explicação

### 🔹 1. O que é um sistema computacional?
Um sistema computacional é composto por:
- Hardware → parte física (CPU, memória, HD)
- Software → programas (sistemas operacionais, aplicativos)

Eles trabalham juntos para processar dados e gerar resultados.

---

### 🔹 2. Hardware básico

#### CPU (Processador)
Responsável por executar instruções.

Componentes principais:
- ULA (Unidade Lógica e Aritmética)
- Unidade de Controle
- Registradores

---

#### Memória
- RAM → volátil (perde dados ao desligar)
- HD/SSD → não volátil

---

#### Barramentos
Permitem a comunicação entre os componentes:

- Barramento de dados → transporta dados
- Barramento de endereço → indica onde acessar
- Barramento de controle → controla operações

---

### 🔹 3. Ciclo de instrução

O processador executa instruções em etapas:

1. Busca (Fetch) → pega instrução da memória  
2. Decodificação (Decode) → entende a instrução  
3. Execução (Execute) → realiza a operação  

Esse ciclo se repete milhões de vezes por segundo.

---

### 🔹 4. Representação binária

Computadores trabalham com 0 e 1 (bits).

Exemplo:
10 (decimal) = 1010 (binário)

Conversão:
- dividir por 2 sucessivamente
- ler restos de baixo para cima

---

### 🔹 5. Sistemas de numeração

Decimal → base 10  
Binário → base 2  
Hexadecimal → base 16  

Exemplo:
255 (decimal) = FF (hexadecimal)

---

### 🔹 6. Compiladores

Transformam código em linguagem de máquina.

Tipos:
- Compilador → traduz tudo de uma vez
- Interpretador → executa linha por linha

Fluxo:
Código Fonte → Compilador → Código de Máquina → Execução

---

## 🔧 Ferramentas relacionadas
- GCC (compilador C)
- Python (interpretado)
- Java (compilado + JVM)
- Visual Studio Code
- Terminal / Prompt

---

## 💻 Exemplo prático

### Exemplo 1: Conversão binária em Python
def decimal_para_binario(n):
    return bin(n)

print(decimal_para_binario(10))

Saída esperada:
0b1010

---

### Exemplo 2: Simulação do ciclo de instrução
instrucao = "SOMA A + B"

print("Buscando instrução...")
print("Decodificando:", instrucao)
print("Executando operação...")

---

### Exemplo 3: Código em C (compilação)
#include <stdio.h>

int main() {
    printf("Hello, World!");
    return 0;
}

Comandos:
gcc programa.c -o programa
./programa

---

## ⚠️ Erros comuns

- Confundir RAM com armazenamento
- Achar que binário não é importante
- Não entender o ciclo de instrução
- Confundir compilador com interpretador
- Ignorar barramentos

---

## 📝 Resumo

- Computador = hardware + software  
- CPU executa instruções em ciclo (fetch, decode, execute)  
- Dados são representados em binário  
- Barramentos conectam os componentes  
- Compiladores traduzem código  

Base essencial para programação.

---

## 📖 Referências

- CORMEN, T. H. et al. Algoritmos.  
- GOODRICH, Michael T.; TAMASSIA, Roberto.  
- ASCENCIO, A.F.G.; CAMPOS, E.A.V.  
- MANZANO, J.A.N.G; OLIVEIRA, J. F.  
- FORBELLONE, A.L.V.; EBERSPACHER, H. F.  

---