# 🐍 Guia Básico de Python

Este documento é uma introdução prática ao Python, ideal para iniciantes.

---

## 📌 O que é Python?

Python é uma linguagem de programação:
- Simples e fácil de aprender
- Muito usada em dados, web, automação e IA
- Multiplataforma (Windows, Linux e Mac)

---

## ▶️ Primeiro Programa

    print("Olá, mundo!")

Rodar no terminal:

    python arquivo.py

---

## 🔤 Variáveis

    nome = "João"
    idade = 20
    altura = 1.75

    print(nome, idade, altura)

---

## 🔢 Tipos de Dados

    texto = "Python"   # string
    inteiro = 10       # int
    decimal = 3.14     # float
    ativo = True       # boolean

---

## 📥 Entrada de Dados

    nome = input("Digite seu nome: ")
    print("Olá,", nome)

---

## 🔀 Condições

    idade = 18

    if idade >= 18:
        print("Maior de idade")
    else:
        print("Menor de idade")

---

## 🔁 Laços

For:

    for i in range(5):
        print(i)

While:

    contador = 0

    while contador < 5:
        print(contador)
        contador += 1

---

## 🧰 Funções

    def saudacao(nome):
        print("Olá,", nome)

    saudacao("João")

---

## 📚 Listas

    frutas = ["maçã", "banana", "uva"]

    print(frutas[0])

    for fruta in frutas:
        print(fruta)

---

## 🗂️ Dicionários

    pessoa = {
        "nome": "João",
        "idade": 20
    }

    print(pessoa["nome"])

---

## 📦 Bibliotecas

    import math

    print(math.sqrt(16))

---

## 🚀 Próximos Passos

- Orientação a objetos  
- Manipulação de arquivos  
- Bibliotecas úteis: Pandas, NumPy, Flask, Django  

---

## 📌 Dicas

- Pratique todos os dias  
- Leia os erros com atenção  
- Crie projetos pequenos  

---

## 📎 Projeto Simples

    # Calculadora

    a = float(input("Número 1: "))
    b = float(input("Número 2: "))

    print("Soma:", a + b)
    print("Subtração:", a - b)
    print("Multiplicação:", a * b)
    print("Divisão:", a / b)

---

## 💡 Conclusão

Python é uma linguagem fácil e poderosa para começar na programação.  
Com prática, você evolui rápido!

---

Autor: João Victor Mendes Ferreira
