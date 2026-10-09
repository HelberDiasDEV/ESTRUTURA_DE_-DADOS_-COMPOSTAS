# Python — Geração de IDs de Estudantes

## Sobre o projeto

Este projeto consiste na resolução de um exercício prático de Python voltado à manipulação de estruturas de dados e à geração de identificadores para estudantes.

A proposta é receber uma lista com os nomes dos estudantes e gerar uma nova lista de tuplas contendo o nome de cada estudante e um código de identificação (ID). O identificador é formado pela primeira letra do nome concatenada a um número aleatório entre 0 e 999.

Além disso, o exercício aborda conceitos importantes de programação, como estruturas de repetição, criação de listas e tratamento de exceções.

## Objetivos

* Praticar a manipulação de listas e tuplas em Python.
* Gerar números aleatórios utilizando a biblioteca `random`.
* Criar identificadores a partir de strings.
* Aplicar laços de repetição para percorrer coleções de dados.
* Compreender a importância do tratamento de exceções.
* Desenvolver boas práticas de programação para evitar erros durante a execução.

## Tecnologias utilizadas

* Python 3
* Google Colab
* Biblioteca `random`

## Funcionamento

O programa utiliza uma lista fictícia com cinco estudantes como entrada. Para cada nome, extrai a primeira letra e concatena um número aleatório entre 0 e 999, formando um identificador.

### Exemplo de entrada

```python
estudantes = ["Ana", "Bruno", "Carlos", "Daniela", "Eduardo"]
```

### Exemplo de saída

```python
[
    ("Ana", "A123"),
    ("Bruno", "B456"),
    ("Carlos", "C78"),
    ("Daniela", "D901"),
    ("Eduardo", "E42")
]
```

Os números apresentados são ilustrativos. A cada execução, os identificadores podem ser diferentes.

## Conceitos praticados

| Conceito           | Aplicação                                     |
| ------------------ | --------------------------------------------- |
| Listas             | Armazenamento dos nomes dos estudantes        |
| Tuplas             | Organização dos nomes e respectivos IDs       |
| Strings            | Extração da primeira letra dos nomes          |
| Laços de repetição | Processamento de cada estudante               |
| Módulo `random`    | Geração de números aleatórios                 |
| Exceções           | Identificação e tratamento de erros em Python |

## Como executar

1. Acesse o notebook no Google Colab.
2. Execute as células na ordem apresentada.
3. Observe a geração dos identificadores e a estrutura da lista de tuplas.
4. Experimente modificar os nomes dos estudantes e executar novamente.

## Aprendizados

Este exercício contribui para o desenvolvimento da lógica de programação e para a compreensão de estruturas de dados essenciais em Python. Também reforça a importância de identificar e tratar exceções para desenvolver códigos mais robustos e confiáveis.

O conhecimento desses fundamentos serve como base para projetos mais avançados nas áreas de desenvolvimento de software, análise de dados e ciência de dados.

---

**Autor:** Helber

**Categoria:** Exercícios de Python

**Ambiente:** Google Colab
