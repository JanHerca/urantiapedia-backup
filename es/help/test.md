---
title: Testing page
description: 
published: true
date: 2022-06-04T17:38:14.733Z
tags: 
editor: markdown
dateCreated: 2022-04-05T10:54:53.296Z
---

The purpose of this page is just for doing tests with content in Markdown files.

---

## Headings

**Markdown**
```
# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading
```
**Result**
<div style="padding-bottom:5px;color: #1565c0; font-size: 2em;font-weight:bold;background:linear-gradient(90deg,#1976d2,rgba(25,118,210,0)) left bottom #fff0 no-repeat;;background-size:100% 3px;">h1 Heading <img src="/_assets/svg/twemoji/1f60e.svg" alt="😎" draggable="false" class="emoji"></div>
<div style="padding-bottom:5px;color: #424242; font-size: 1.5em;font-weight: bold;background:linear-gradient(90deg,#424242,rgba(25,118,210,0)) left bottom #fff0 no-repeat;;background-size:100% 1px;">h2 Heading</div>
<div style="padding-bottom:5px;color: #616161; font-size: 1.17em;font-weight: bold;background:linear-gradient(90deg,#616161,rgba(25,118,210,0)) left bottom #fff0 no-repeat;;background-size:100% 1px;">h3 Heading</div>
<div style="padding-bottom:5px;color: #616161; font-weight: bold;background:linear-gradient(90deg,#616161,rgba(25,118,210,0)) left bottom #fff0 no-repeat;;background-size:100% 1px;">h4 Heading</div>
<div style="padding-bottom:5px;color: #616161; font-weight: bold;background:linear-gradient(90deg,#616161,rgba(25,118,210,0)) left bottom #fff0 no-repeat;;background-size:100% 1px;">h5 Heading</div>
<div style="padding-bottom:5px;color: #616161; font-weight: bold;background:linear-gradient(90deg,#616161,rgba(25,118,210,0)) left bottom #fff0 no-repeat;;background-size:100% 1px;">h6 Heading</div>


## Horizontal Rules

**Markdown**
```
___
---
***
```

**Result**
___
---
***

## Typographic replacements

Enable typographer option to see result.

**Markdown**
```
(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'
```

**Result**

© © ® ® ™ ™ § § ±

test… test… test… test?.. test!..

!!! ??? , – —

“Smartypants, double quotes” and ‘single quotes’

## Emphasis

**Markdown**
```
**This is bold text**
__This is bold text__
*This is italic text*
_This is italic text_
~~Strikethrough~~
***Bold & italic***
```

**Result**
**This is bold text**
__This is bold text__
*This is italic text*
_This is italic text_
~~Strikethrough~~
***Bold & italic***

## Blockquotes

**Markdown**
```
> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.
```
**Result**
> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

Custom blockquotes
**Markdown**
```
> This is an info blockquote
{.is-info}

> This is a success blockquote
{.is-success}

> This is a warning blockquote
{.is-warning}

> This is an error blockquote
{.is-danger}
```
**Result**
> This is an info blockquote
{.is-info}

> This is a success blockquote
{.is-success}

> This is a warning blockquote
{.is-warning}

> This is an error blockquote
{.is-danger}

## Lists

### Unordered

**Markdown**
```
+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!
```
**Result**
+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

### Ordered

**Markdown**
```
1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`
```
**Result**
1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

### Start numbering with offset:

**Markdown**
```
57. foo
1. bar
```
**Result**
57. foo
1. bar

## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

**Markdown**

```
| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |
```

**Result**

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

**Markdown**

```
| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |
```

**Result**

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

## Links


**Markdown**

```
[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)
```

**Result**

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)


## Images

**Markdown**
```
![Minion](https://octodex.github.com/images/minion.png) {#Letter_figure_1 .image.image_resized}
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")
```

**Result**
![Minion](https://octodex.github.com/images/minion.png) {#Letter_figure_1 .image.image_resized}
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

**Markdown**
```
![Alt text][id]
```

**Result**
![Alt text][id]

With a reference later in the document defining the URL location:

**Markdown**
```
[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"
```

**Result**
[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


## Plugins

The killer feature of `markdown-it` is very effective support of [syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.


### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

- 19^th^
- H~2~O


### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++


### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

==Marked text==


### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.


### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1
with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

_Compact style:_

Term 1
  ~ Definition 1

Term 2
  ~ Definition 2a
  ~ Definition 2b


### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::

### [Advanced tables](https://github.com/RedBug312/markdown-it-multimd-table)

#### With grouping, alignment, and scaping

|             |          Grouping           ||
First Header  | Second Header | Third Header |
 ------------ | :-----------: | -----------: |
Content       |          *Long Cell*        ||
Content       |   **Cell**    |         Cell |

New section   |     More      |         Data |
And more      | With an escaped \|       ||
[Prototype table]

#### With multiline

|   Markdown   | Rendered HTML |
|--------------|---------------|
|    *Italic*  | *Italic*      | \
|              |               |
|    - Item 1  | - Item 1      | \
|    - Item 2  | - Item 2      |
|    ```python | ```python       \
|    .1 + .2   | .1 + .2         \
|    ```       | ```           |

#### With rowspan

Stage | Direct Products | ATP Yields
----: | --------------: | ---------:
Glycolysis | 2 ATP ||
^^ | 2 NADH | 3--5 ATP |
Pyruvaye oxidation | 2 NADH | 5 ATP |
Citric acid cycle | 2 ATP ||
^^ | 6 NADH | 15 ATP |
^^ | 2 FADH2 | 3 ATP |
**30--32** ATP |||
[Net ATP yields per hexose]

| Archetypes ||
--- | ---
Adam and Eve | Faith 
Lucifer | Prophecy 
Satan Guardian | Angels 
Melchizedek | Life after death 
Seraphim | The Kingdom of Heaven 
Heaven | The Apostles 
Hell | Jesus and the stories of His Life and Teachings 
Salvation | The “Second Coming” 

We are the creatures who carry the life. 
We strive hard to make you your life. 
We are your ancestors. 
We are the ones who helped make you possible. 

### [Mathjax](https://github.com/classeur/markdown-it-mathjax)

Processes TeX displayed math

$$1 *2* 3$$

Processes TeX in-line math $1 *2* 3$

When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

$$\frac{1}{\sqrt{x^2 + 1}}$$

__O^1^ O^2^ O^3^ O^4^ O^5^ O^6^ O^7^ O^8^ O^9^ <u>O</u>^10^ O^11^ O^12^__

$$V = H_0 * D, $$

In most part yes, in $1/4$ no.

description	| code | examples
--- | --- | ---
Greek letters |	\alpha \beta \gamma \rho \sigma \delta \epsilon	| $\alpha \beta \gamma \rho \sigma \delta \epsilon$
Binary operators | \times \otimes \oplus \cup \cap | $\times \otimes \oplus \cup \cap$
Relation operators | < > \subset \supset \subseteq \supseteq | $< > \subset \supset \subseteq \supseteq$
Others | \int \oint \sum \prod | $\int \oint \sum \prod$

$$ \max dS/dt = \pm \begin{cases} wR, R \leq D \\ wD, R \geq D  \end{cases}$$

Earth mass = $M^\odot$

See [Mathjax](https://www.mathjax.org/)
See [Mathjax documentation](http://docs.mathjax.org/en/latest/index.html)
See [LaTeX Math expressions](https://www.overleaf.com/learn/latex/Mathematical_expressions)



