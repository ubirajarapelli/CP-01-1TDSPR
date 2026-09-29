# 🍽️ Checkpoint — Sabor da Casa

## HTML, Web Semântica e CSS

Neste checkpoint você vai receber uma página de restaurante construída **propositalmente sem utilizar HTML semântico**.

Sua tarefa é analisar a estrutura existente e aplicar os conhecimentos de **HTML, Web Semântica e CSS** trabalhados até agora.

---

## 🎯 Objetivos

Ao finalizar o exercício, você deverá demonstrar que consegue:

- reconhecer a função dos principais elementos HTML;
- utilizar uma hierarquia adequada de títulos;
- identificar quando um conteúdo representa uma lista;
- utilizar elementos semânticos de estrutura de página;
- diferenciar conteúdo de navegação, conteúdo principal e conteúdo independente;
- aplicar CSS básico;
- compreender e utilizar o Box Model.

---

# 📋 Parte 1 — HTML e Web Semântica

O arquivo `index.html` foi criado propositalmente utilizando principalmente:

- `div`
- `span`

Sua primeira tarefa é **substituir as estruturas genéricas pelos elementos HTML mais adequados**.

### Atenção

Não basta trocar todas as `div` por tags semânticas aleatoriamente.

Analise o significado de cada conteúdo e escolha o elemento mais adequado.

Você deverá considerar, entre outros:

- cabeçalho da página;
- conteúdo principal;
- rodapé;
- seções do cardápio;
- itens individuais do cardápio;
- títulos;
- textos;
- possíveis listas;
- links, caso sejam necessários.

### Regra

O resultado final deve utilizar **HTML semântico sempre que houver um elemento apropriado para representar aquele conteúdo**.

Evite manter `div` e `span` quando existir um elemento HTML mais adequado para aquela finalidade.

---

# 🎨 Parte 2 — CSS (Box Model)

O projeto já possui um CSS básico para que você possa se concentrar na estrutura HTML.

Você deverá ajustar o CSS caso seja necessário para que a página continue visualmente organizada depois das alterações no HTML.

### Requisitos

A página deve possuir:

- uma largura adequada para o conteúdo;
- espaçamento interno utilizando `padding`;
- espaçamento externo utilizando `margin`;
- bordas nos itens do cardápio;
- cores para diferenciar as áreas da página;
- hierarquia visual entre títulos e textos;
- imagens com tamanho adequado;
- utilização de `box-sizing: border-box`;

### ⚠️ Importante

**Não é necessário utilizar:**

- Flexbox;
- CSS Grid;
- `float`;
- posicionamento absoluto.

---

### Analise os elementos do cardápio e utilize corretamente:

```css
margin
padding
border
width
height
box-sizing
```


### Desafio

Alinhamento horizontal dos items do cardápio. Altere seus valores de `padding`, `border` e `margin`.

Observe o resultado no navegador e no DevTools.

---

# ✅ Checklist antes de entregar

Antes de enviar seu projeto, verifique:

- [ ] A página possui uma estrutura semântica.
- [ ] Existe apenas um `h1` representando o título principal.
- [ ] Os demais títulos respeitam uma hierarquia.
- [ ] O conteúdo principal está identificado semanticamente.
- [ ] O cabeçalho está identificado semanticamente.
- [ ] O rodapé está identificado semanticamente.
- [ ] As seções do cardápio estão semanticamente identificadas.
- [ ] Os itens do cardápio utilizam elementos adequados ao seu significado.
- [ ] Listas foram utilizadas quando apropriado.
- [ ] As imagens possuem `alt` descritivo.
- [ ] `margin`, `padding` e `border` foram compreendidos e utilizados.
- [ ] `box-sizing` foi utilizado.
- [ ] Os itens continuam um abaixo do outro.
- [ ] Não foi utilizado Flexbox ou Grid.
- [ ] O arquivo `RESPOSTAS.md` foi preenchido.
- [ ] O projeto abre corretamente no navegador.

---

## 💡 Dica

Antes de escrever qualquer código, leia o conteúdo da página e pergunte:

> **"O que esse conteúdo significa?"**

Depois procure o elemento HTML que melhor representa esse significado.

HTML semântico não é escolher uma tag porque ela deixa o texto maior ou menor. É escolher a tag de acordo com o **papel daquele conteúdo dentro da página**.

Bom trabalho! 🍽️
