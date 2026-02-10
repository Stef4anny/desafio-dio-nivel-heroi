# 🦸‍♂️ Classificador de Nível de Herói

Este projeto foi desenvolvido como parte de um **desafio prático da DIO (Digital Innovation One)**, com o objetivo de aplicar e consolidar conceitos fundamentais de **lógica de programação em JavaScript**.

O sistema permite informar o **nome do herói** e sua **quantidade de experiência (XP)** e, a partir disso, classifica automaticamente o herói em um **nível**.

---

## 🎯 Objetivo do Desafio

Criar um algoritmo que:

* Armazene o **nome** e a **quantidade de XP** de um herói
* Utilize **estruturas de decisão** para classificar o nível do herói
* Exiba a mensagem final:

```
O Herói de nome {nome} está no nível de {nivel}
```

---

## 🧠 Conceitos Utilizados

Neste projeto foram aplicados os seguintes conceitos de programação:

* ✅ Variáveis
* ✅ Operadores lógicos e relacionais
* ✅ Estrutura de decisão (`switch case`)
* ✅ Manipulação de DOM
* ✅ Eventos (`submit`)

> 🔎 Observação: apesar do desafio mencionar laços de repetição, a lógica de classificação não exige iteração. Optei por priorizar **clareza e boas práticas**, evitando o uso de laços artificiais apenas para cumprir requisito.

---

## 🏆 Regras de Classificação

| XP do Herói             | Nível      |
| ----------------------- | ---------- |
| Menor que 1.000         | Ferro      |
| 1.001 – 2.000           | Bronze     |
| 2.001 – 5.000           | Prata      |
| 5.001 – 7.000           | Ouro       |
| 7.001 – 8.000           | Platina    |
| 8.001 – 9.000           | Ascendente |
| 9.001 – 10.000          | Imortal    |
| Maior ou igual a 10.001 | Radiante   |

---

## 💻 Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (Vanilla JS)

---

## 📸 Demonstração

O usuário informa:

* Nome do herói
* Quantidade de XP

Ao clicar em **Enviar**, o sistema retorna uma mensagem com o nível correspondente ao XP informado.

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

2. Abra o arquivo `index.html` no navegador

---

## 📌 Possíveis Melhorias Futuras

* Exibir o resultado diretamente na tela (sem `alert`)
* Criar um layout mais elaborado para exibição do nível
* Implementar validações adicionais de entrada
* Adicionar testes básicos de lógica

---

## 👩‍💻 Autora

**Stefanny Izidoro**
Desenvolvedora de Software Fullstack
Formada em Análise e Desenvolvimento de Sistemas

🔗 GitHub: [https://github.com/seu-usuario](https://github.com/seu-usuario)

---

✨ Projeto desenvolvido para fins educacionais e de portfólio.
