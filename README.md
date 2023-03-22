
# Welcome to CDietinger!

I'm the readme.md; default Markdown file of Sample Repository inside **CDietinger**.

If you want to play with Markdown files, you can edit me right here by clicking the pen or in VSCode or any of the online editors like:

- https://onlinemarkdowneditor.dev/
- https://pandao.github.io/editor.md/en.html

 Note that Markdown is rather simple text formatting codex -  one can create markdown files even in Notepad!

# Embed code

```js

/*
Store exothermic reaction in two Maps:
mapStart and mapEnd
*/

// create maps
const mapStart = new Map();
const mapEnd = new Map();

// Add values to the maps
mapStart.set('Na', 2');
mapStart.set('Cl', '2');

mapEnd.set('NaCl', 2');


```


# Markdown extensions

Standard Markdown syntax can be extended by adding extra **Markdown extensions**.

> **ProTip:** Check `mathpix.vscode-mathpix-markdown` form VSCode or  for general markdown:`mhchem` https://docs.moodle.org/401/en/Chemistry_notation_using_mhchem


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).

