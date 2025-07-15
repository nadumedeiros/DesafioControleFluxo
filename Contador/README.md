# 🧮 Desafio: Controle de Fluxo em Java

Este projeto tem como objetivo exercitar o conteúdo de **controle de fluxo** em Java, utilizando **entrada de dados via terminal**, **laços de repetição (`for`)** e **tratamento de exceções personalizadas**.

---

## 📋 Descrição do programa

O programa lê **dois números inteiros** informados pelo usuário através do terminal:

- Se o **segundo número for maior** que o primeiro, o programa imprime uma sequência de mensagens no formato:

Imprimindo o número 1
Imprimindo o número 2

- O número de mensagens é igual à **diferença entre o segundo e o primeiro número**.

- Se o **primeiro número for maior que o segundo**, o programa lança e trata uma **exceção personalizada**, exibindo a mensagem:

O segundo parametro deve ser maior que o primeiro


---

## 🧠 Exemplo de uso

### Entrada:
Digite o primeiro parâmetro:
5
Digite o segundo parâmetro:
9

### Saída:
Imprimindo o numero 1
Imprimindo o numero 2
Imprimindo o numero 3
Imprimindo o numero 4


## 📦 Estrutura do projeto

DesafioControleFluxo/
├── Contador.java
├── ParametrosInvalidosException.java

yaml
Copiar
Editar

### `Contador.java`
Contém a lógica principal do programa: leitura de parâmetros, contagem e tratamento de exceções.

### `ParametrosInvalidosException.java`
Classe de exceção personalizada usada para sinalizar que os parâmetros foram passados em ordem incorreta.

---

## ▶️ Como compilar e executar

### 1. Compile os arquivos:

```bash
javac ParametrosInvalidosException.java Contador.java
2. Execute o programa:
bash
Copiar
Editar
java Contador
