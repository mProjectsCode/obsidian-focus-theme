## Horizontal Rules

---

---

---

## Emphasis

**This is bold text**

**This is bold text**

_This is italic text_

_This is italic text_

_**This is bold and italic text**_

_**This is bold and italic text**_

This is normal text

This is normal text

==This is highlighted text==

==This is highlighted text==

~~Strikethrough~~

~~Strikethrough~~

## Colors

<span style="color: var(--color-red)">Text test, yes Some Text...</span>

<span style="color: var(--color-green)">Text test, yes Some Text...</span>

<span style="color: var(--color-orange)">Text test, yes Some Text...</span>

<span style="color: var(--color-yellow)">Text test, yes Some Text...</span>

<span style="color: var(--color-cyan)">Text test, yes Some Text...</span>

<span style="color: var(--color-blue)">Text test, yes Some Text...</span>

<span style="color: var(--color-purple)">Text test, yes Some Text...</span>

<span style="color: var(--color-pink)">Text test, yes Some Text...</span>

## Blockquotes

> Blockquotes can also be nested...
>
> > ...by using additional greater-than signs right next to each other...
> >
> > > ...or with spaces between arrows.
> > > teste

> [!info]
> test
>
> > [!Info]
> > asd
> >
> > | Option |                                                               Description |
> > | -----: | ------------------------------------------------------------------------: |
> > |   data | path to data files to supply the data that will be passed into templates. |
> > | engine |    engine to be used for processing templates. Handlebars is the default. |
> > |    ext |                                      extension to be used for dest files. |
> 
> > i am a quote
> 
> > [!success]
> > i am a warning, be scared

> > [!warning]
> > i am a warning, be scared

> [!warning]
> I am a warning, be scared

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

```js
var foo = function (bar) {
	return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description                                                               |
| ------ | ------------------------------------------------------------------------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default.    |
| ext    | extension to be used for dest files.                                      |

Right aligned columns

| Option |                                                               Description |
| -----: | ------------------------------------------------------------------------: |
|   data | path to data files to supply the data that will be passed into templates. |
| engine |    engine to be used for processing templates. Handlebars is the default. |
|    ext |                                      extension to be used for dest files. |

| asdasd | test | asdasd | asdas | asdasd |
| ------ | ---- | ------ | ----- | ------ |
| dxcvdf | gfgh | fghdfg | ada   | hry    |
| asd    | dfg  | asd    | fa    | dfgzd  |
| asd    | dfg  | asd    | asd   | dzxcv  |

## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ 'title text!')

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)

## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg 'The Stormtroopocat')

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg 'The Dojocat'

## Plugins

The killer feature of `markdown-it` is very effective support of
[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).

### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.

### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

-   19^th^
-   H~2~O

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

: Definition 1
with lazy continuation.

Term 2 with _inline markup_

: Definition 2

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

\*[HTML]: Hyper Text Markup Language
