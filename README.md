# 🧮 Calculadora Simples em Python

Este projeto é uma **calculadora simples em Python**, criada com o objetivo de praticar lógica de programação e versionamento de código utilizando Git e GitHub.

---

## 🚀 Funcionalidades
- Soma
- Subtração
- Multiplicação
- Divisão
- Tratamento de erro para divisão por zero

---

## 🛠 Tecnologias utilizadas
- Python 3

---

## 📂 Estrutura do projeto

---

## ▶️ Como executar o projeto

1. Certifique-se de ter o **Python 3** instalado  
2. Clone este repositório ou baixe os arquivos  
3. No terminal, acesse a pasta do projeto  
4. Execute o comando:

```bash
python calculadora.py

calculadora-python/
 ├── calculadora.py
 └── README.md


def soma(a, b):
    return a + b

def subtracao(a, b):
    return a - b

def multiplicacao(a, b):
    return a * b

def divisao(a, b):
    if b == 0:
        return "Erro: divisão por zero"
    return a / b

print("Calculadora Simples")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

opcao = input("Escolha uma opção: ")
a = float(input("Digite o primeiro número: "))
b = float(input("Digite o segundo número: "))

if opcao == "1":
    print("Resultado:", soma(a, b))
elif opcao == "2":
    print("Resultado:", subtracao(a, b))
elif opcao == "3":
    print("Resultado:", multiplicacao(a, b))
elif opcao == "4":
    print("Resultado:", divisao(a, b))
else:
    print("Opção inválida")
