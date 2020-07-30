## writing with latex
### basics
LaTeX is a programming language that translates code (plain text, as usually) into pretty documents.

You use a text editor of your choice (Notepad, SublimeText, Atom etc.) to write the code, then you _compile_ it to produce the document. Note the difference between a _text editor_ (e.g. Notepad) and a _development environment_ (e.g. Texmaker or TeXworks). The latter is a convenient program to work with a programming language, harboring tools to compile and run code. The usual tradeoff between flexibility and extensibility on the one hand and operational simplicity on the other applies.

### setup
*   [from here](https://www.tug.org/texlive/acquire-netinstall.html)
*   select 'medium' for scheme (~1.5 GB instead of 7 GB)
*   test installation, see [here](https://www.tug.org/texlive/doc/texlive-en/texlive-en.html#x1-380003.5)

### packages
To install a new package, you need to locate it in the distribution you are using (TeX Live in our case).
> [https://ctan.org/pkg/threeparttable?lang=en](https://ctan.org/pkg/threeparttable?lang=en)

Then, use either TeX Live Manager or `tlmgr install threeparttable` to install it, then refresh the TeX database with `texhash`