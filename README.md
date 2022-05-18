# Markdown ⚡
Dica e estudos sobre essa linguagem de marcação!

### O que é Markdown? 👨🏻‍💻
Markdown é uma linguagem de marcação leve que escreve documentos em texto simples **(fácil de ler, fácil de escrever, fácil de mudar)** e eventualmente publicado em formato HTML.
O markdown também pode ser entendido como uma ferramenta que converte um idioma escrito com sintaxe de marcação em conteúdo HTML, também pode se utilizar algumas tags html em arquivos markdown.

---

#### Links para estilizar melhor o seu Markdown 👊

+ [Pegar emojis](https://emojipedia.org/)
+ [Dev Icons](https://devicon.dev/)

### Atalhos 😉

| 1º | 2º | 3º |
|----|----|----|
| [Citação](#Citação) | [Fontes](#Fontes) | [Links](#Links) |
| [Título](#Título) | [Lista](#Lista) | [Imagens](#Imagens) |
| [Dividers](#Dividers) | [CheckBox](#CheckBox) | [Imagens dentro das tabelas](#ImgTabelas) |
| [Barra Invertida](#BarraInvertida) | [Texto de seta](#SetaText) | [Tabela](#Tabela) |

---

# Markdown syntax 💻

<h2 id="Citação">Citação</h2>

```markdown
> texto
> > texto aninhado
```

Efeito:
> citação
> > citação aninhada

---

<h2 id="Título">Título</h2>

#### use '#' para representar as Headings nível 1-6.

```markdown
# Título **h1**
## Título **h2**
### Título **h3**
##### Título **h4**
####### Título **h5**
######### Título **h6**
```

---

Efeito:
> + # Título
> + ## Título
> + ### Título
> + #### Título
> + ##### Título
> + ###### Título

#### Note que quando temos um ou dois `#` aparece uma linha em baixo do título.

<h2 id="Dividers">Dividers</h2>
são as linhas grandes para dividir as sessões

```markdown
***
ou
---
```

<h2 id="BarraInvertida">Backslash** _(Barra Invertido)_ **`\`*</h2>
A **Barra Invertido**. faz com que você consiga mostrar alguma sintaxe do markdown.

---

<h2 id="Fontes">Fontes</h2>
adicione '**' ou '__' a cada lado da ênfase, tais como:

| FONTE | SINTAXE | EFEITO |
|-------|---------|--------|
| italic | \_italic_ | _italic_ |
| bold | \**bold** |  **bold** |
| bold | \__bold__ |  __bold__ |

---

<h2 id="Lista">lista</h2>
marque listas não ordenadas com '·', '+'ou '-' tais como:

```markdown
+  Item
*  Item
-  Item
```

Efeito:

> + primeiro item usando o '+'
> + segundo item usando o `+`
> + terceiro item usando o `+`

> * primeiro item usando o `*`
> * segundo item usando o `*`
> * terceiro item usando o `*`

> - item 1 usando o `-`
> - item 2 usando o `-`
> - item 3 usando o `-`
---

<h2 id="CheckBox">Checkbox</h2>

```markdown
- [ ] Itens
- [x] Itens
 - [x] Itens 2
- [ ] Itens
```

Efeito:

> - [ ] Itens
> - [x] Itens
>   - [x] Itens
> - [ ] Itens

---

<h2 id="SetaText">Texto de seta:</h2>

<details>
  <summary>Título</summary>
  <p>Conteúdo</p>
</details>

---

<h2 id="Codes">Codes</h2>

### Inline Code
Run terminal \`npm install\` or \`yarn install\`

Efeito:
Run terminal `npm install` or `yarn install`


### Code block

> \`\`\`js <br/>
> alert('Hello World!') <br/>
> \`\`\`

Efeito:
```js
alert('Hello World!')
```


---


<h2 id="Links">Links</h2>
links podem ser gerados em duas formas: linha em linha e referência.


**Linha em linha**:

```markdown
[Biblioteca Markdown do João](https:://github.com/joaovic-tech/markdown "Markdown")
```

### Nota: Esse "Markdown" no final do link cria um caixa de texto ao passar o mouse por cima

Efeito:
> [Biblioteca Markdown do João](https:://github.com/joaovic-tech/markdown "Markdown")

**referências**:

```markdown
> [Dicas de Markdown 1][1] 
> [Dicas de Markdown 2][2]

[1]: https:://github.com/joaovic-tech/markdown "Markdown"
[2]: https:://github.com/joaovic-tech/markdown "Markdown"
```

Efeito:
> [Dicas de Markdown 1][1] 
> [Dicas de Markdown 2][2]

[1]: https:://github.com/joaovic-tech/markdown "Markdown"
[2]: https:://github.com/joaovic-tech/markdown "Markdown"

---

<h2 id="Imagens">Imagens</h2>
adicione uma imagem de forma semelhante a um link, basta adicionar um '!' antes do []

```markdown
![My cartton](https://avatars.githubusercontent.com/u/79641024?v=4)
```

Efeito:
> ![My cartton](https://avatars.githubusercontent.com/u/79641024?v=4)

<h2 id="ImgTabelas">Imagens dentro das tabelas</h2>

```markdown
<h4 align="center">🌙Cartoon🔆</h4>

| Coluna 1                                     | Coluna 2                                            |
|:-------------------------------------------------:|:-----------------------------------------------:|
| ![](https://avatars.githubusercontent.com/u/79641024?v=4)  | ![](https://avatars.githubusercontent.com/u/79641024?v=4)         |
| Cartoon 1                                   | Cartoon 2                                 |
| ![](https://avatars.githubusercontent.com/u/79641024?v=4) | ![](https://avatars.githubusercontent.com/u/79641024?v=4) |
| Cartoon 3                                     | Cartoon 4                                        |
| ![](https://avatars.githubusercontent.com/u/79641024?v=4)  | ![](https://avatars.githubusercontent.com/u/79641024?v=4)     |

```

Efeito:
<h4 align="center">🌙Cartoon🔆</h4>

| Coluna 1                                     | Coluna 2                                            |
|:-------------------------------------------------:|:-----------------------------------------------:|
| ![](https://avatars.githubusercontent.com/u/79641024?v=4)  | ![](https://avatars.githubusercontent.com/u/79641024?v=4)         |
| Cartoon 1                                   | Cartoon 2                                 |
| ![](https://avatars.githubusercontent.com/u/79641024?v=4) | ![](https://avatars.githubusercontent.com/u/79641024?v=4) |
| Cartoon 3                                     | Cartoon 4                                        |
| ![](https://avatars.githubusercontent.com/u/79641024?v=4)  | ![](https://avatars.githubusercontent.com/u/79641024?v=4)     |
| Cartoon 5                                     | Cartoon 6                                        |

---

<h2 id="Tabela">Tabela</h2>

#### **primeiro estilo da tabela**

```markdown
_| Type | Date
_|-|-|
_| A | 2077 |
_| B | 1998 |
_| C | 1864 |
_| D | 1722 |
```

Efeito:
> | Type | Date|
> |-|-|
> | A | 2077|
> | B | 1998|
> | C | 1864|
> | D | 1722|

#### **segundo estilo da tabela**

```markdown
| Type | Date
|:---:|:---:|
| A | 2077 |
| B | 1998 |
| C | 1864 |
| D | 1722 |
```

Efeito:
>  | Type | Date|
>  |:---:|:---:|
>  | A | 2077|
>  | B | 1998|
>  | C | 1864|
>  | D | 1722|