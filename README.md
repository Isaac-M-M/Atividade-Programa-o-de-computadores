# Estudo Dirigido: Estruturas de Controle do Fluxo de Execução

## Introdução

Durante o desenvolvimento de algoritmos, é preciso controlar a ordem em que as instruções são executadas. Para isso, utilizamos as chamadas *estruturas de controle de fluxo*, que permitem organizar e definir como o programa se comporta em diferentes situações.

No estudo de lógica e programação, existem três tipos principais de estruturas:

1. *Sequencial:* Instruções executadas linha por linha, na ordem em que aparecem no código.
2. *Decisão:* Permite escolher entre caminhos diferentes, dependendo de condições (usando if, else, elif).
3. *Repetição:* Repete blocos de código enquanto uma condição for verdadeira (while) ou para uma sequência definida (for).

Este estudo dirigido tem como objetivo *aplicar essas três estruturas básicas em programas simples escritos em Python, com base no conteúdo apresentado no livro *Algoritmos e Programação I. Ao final, os códigos serão organizados e armazenados em um repositório no GitHub.

## Recurso Teórico
Livro: **Algoritmos e Programação I**  
[Link para o livro](https://educapes.capes.gov.br/bitstream/capes/176223/2/Algoritmos%20e%20Programa%C3%A7%C3%A3o%20I%20EBOOK.pdf)

### Capítulos indicados:
- Estruturas de Controle (p. 103)
- Estrutura Sequencial (p. 104)
- Estruturas de Decisão (p. 114)
- Estruturas de Repetição (p. 135)

---

### 2. Estrutura Sequencial (10 min)

**Conceito:**  
Comandos executados de cima para baixo, em ordem.

**Atividade:**  
Peça dois números, some-os e mostre o resultado.

**Exemplo de código:**
```python
numero1 = float(input("Digite o primeiro número: "))
numero2 = float(input("Digite o segundo número: "))
soma = numero1 + numero2
print("A soma é:", soma)
```

**Arquivo:** `sequencial.py`

---

### 3. Estrutura de Decisão (15 min)

**Conceito:**  
Usar if, else e elif para decisões no programa.

**Atividade:**  
Verifique a idade e imprima se é maior, menor ou exatamente 18 anos.

**Exemplo de código:**
```python
idade = int(input("Digite sua idade: "))
if idade > 18:
    print("Você é maior de idade")
elif idade == 18:
    print("Você tem exatamente 18 anos")
else:
    print("Você é menor de idade")
```

**Arquivo:** `decisao_idade.py`

---

### 4. Estruturas de Repetição (15 min)

#### WHILE
**Atividade:**  
Imprima os números de 1 a 5 com `while`.

```python
contador = 1
while contador <= 5:
    print(contador)
    contador += 1
```

**Arquivo:** `repeticao_while.py`

#### FOR
**Atividade:**  
Imprima os números de 1 a 5 com `for`.

```python
for i in range(1, 6):
    print(i)
```

**Arquivo:** `repeticao_for.py`

---

## 5. Encerramento (5 min)
- Recapitular conceitos.
- Estimular dúvidas e testes extras.
- Reforçar o uso do GitHub.

---

## Instruções para o GitHub

1. Criar um repositório chamado `programacao-de-computadores`.
2. Criar a pasta: `atividades praticas de Programação de computadores`.
3. Adicionar os arquivos:
   - `sequencial.py`
   - `decisao_idade.py`
   - `repeticao_while.py`
   - `repeticao_for.py`
