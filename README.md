# Markdown 😉
Dica e estudos sobre essa linguagem de marcação!

### O que é Markdown?
Markdown é uma linguagem de marcação leve que escreve documentos em texto simples **(fácil de ler, fácil de escrever, fácil de mudar)** e eventualmente publicado em formato HTML.
O markdown também pode ser entendido como uma ferramenta que converte um idioma escrito com sintaxe de marcação em conteúdo HTML, também pode se utilizar tags html em arquivos markdown porem não vou aborda aqui.

---

#### Links para estilizar melhor o seu Markdown

+ [Pegar emojis](https://emojipedia.org/)
+ [Dev Icons](https://devicon.dev/)

---

# Markdown syntax

## **Citação**

```markdown
> texto
> > texto aninhado
```

Efeito:
> citação
> > citação aninhada

---

## **Título**

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

## **Dividers**
são as linhas grandes para dividir as sessões

```markdown
***
ou
---
```

## **Backslash** _(Barra Invertido)_ **`\`**
A **Barra Invertido**. faz com que você consiga mostrar alguma sintaxe do markdown.

---

## **Fontes**
adicione '**' ou '__' a cada lado da ênfase, tais como:

| FONTE | SINTAXE | EFEITO |
|-------|---------|--------|
| italic | \_italic_ | _italic_ |
| bold | \**bold** |  **bold** |
| bold | \__bold__ |  __bold__ |

---

## **lista**
marque listas não ordenadas com '·', '+'ou '-' tais como:

```markdown
+  Item
*  Item
-  Item
```

Efeito:
\+
> + primeiro item
> + segundo item
> + terceiro item
\*
> * primeiro item
> * segundo item
> * terceiro item
\-
> - item 1
> - item 2
> - item 3

---

## **Lista Checkbox**

```markdown
+ [ ] Itens
+ [x] Itens
 + [x] Itens 2
+ [ ] Itens
```

Efeito:

> + [ ] Itens
> + [x] Itens
>   + [x] Itens
> + [ ] Itens

---

## **Codes**

### Inline Code
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


## **Links**
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
[Biblioteca Markdown 1][1] 
[Biblioteca Markdown  2][2]
[1]:https:://github.com/joaovic-tech/Markdown "Markdown"
[2]:https:://github.com/joaovic-tech/Markdown "Markdown"
```

Efeito:

[Biblioteca Markdown 1][1] 
[Biblioteca Markdown  2][2]
[1]:https:://github.com/joaovic-tech/Markdown "Markdown"
[2]:https:://github.com/joaovic-tech/Markdown "Markdown"

---

## **Imagens**
adicione uma imagem de forma semelhante a um link, basta adicionar um '!' antes do []

```markdown
![My cartton](https://avatars.githubusercontent.com/u/79641024?v=4)
```

Efeito:
> ![My cartton](https://avatars.githubusercontent.com/u/79641024?v=4)

---

## **Tabela**
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