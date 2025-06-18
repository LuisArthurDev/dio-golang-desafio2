# 🔢 Desafio – Resolvendo Problemas Numéricos com Go

Projeto desenvolvido no curso **Formação Go Developer** da [DIO](https://www.dio.me/), com foco na prática de algoritmos simples em Go (Golang).

---

## 📝 Descrição

O programa percorre os números de **1 a 100** e, para cada valor:

- Se o número for **divisível por 3**, imprime **“Pin”**.  
- Se o número for **divisível por 5**, imprime **“Pan”**.  
- Se o número for divisível **por 3 e 5 ao mesmo tempo**, imprime **“PinPan”**.  
- Caso contrário, imprime o próprio número.

> ℹ️ Esta variação do clássico *FizzBuzz* ajuda a fixar o uso de laços de repetição, operadores aritméticos e condicionais em Go.

---

## 🎯 Objetivos de Aprendizado

- Declarar e inicializar variáveis em Go  
- Utilizar o laço `for` para iteração  
- Empregar operadores de resto (`%`) para checar divisibilidade  
- Trabalhar com estruturas condicionais (`if / else if / else`)  
- Escrever código limpo e bem comentado

---

## 🚀 Tecnologias

- **Go (Golang)** – versão 1.22 ou superior  
- **Git & GitHub** – versionamento do código  
- Terminal ou IDE de sua preferência (VS Code, GoLand, etc.)

---

## 📁 Estrutura do Projeto
```
├── main.go # Código-fonte do desafio
└── README.md # Este documento
```
---

## 🖥️ Como Executar

1. **Clone** o repositório:
   ```
   git clone https://github.com/seu-usuario/nome-do-repo.git
   cd nome-do-repo
   ```
2. Execute o programa:

```
go run main.go
```
💡 Exemplo de Saída
```
1
2
Pin
4
Pan
Pin
7
8
Pin
Pan
11
Pin
13
14
PinPan
...
```
Desenvolvido por Luis Arthur
