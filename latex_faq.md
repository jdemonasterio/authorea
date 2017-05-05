# LATEX SUCKS
It's great for typesetting, formatting, styling,etc. But prograaming-wise, it sucks.

Finding bugs, typos and errors is super difficult. One generally resorts to comment out a whole block of code where the bug is and later apply a "binary search" of the bug by uncommenting parts of it.


## OSX Package Manager
The default Tex distribution in OSX is MacTex http://tug.org/mactex/mactex-download.html which includes most of the commonly used packages. It also comes with a TexLive Utility tool to update MacTex, update packasges or install packages.

## How to manually install tex packages
(Follow this directory structure: http://tex.stackexchange.com/questions/8357/how-to-have-local-package-override-default-package/8359#8359)

	* Download `.sty` file from CTAN.
	* move it to ~/Library/texmf/tex/latex (mkdir if dir not available).
	* Tex will find it.
	* If necessary: move doc files following the correct dir structures

## Working environment
The following packages are needed to run `main.tex` which build the Thesis .pdf . Even if you have them all, please consider upgrading (known bugs with older versions, mostly on missing arguments.).

* biber
* biblatex
* comments
* graphicx
* algorithm2e
* qtree

## Common Thesis Bugs

* opened `(`, `{` or `[` which are not closed..

* You can't use the usual bold inside a math environment i.e.
don't $\textbf{y}$ --> use $\boldsymbol{y}$

* You can't use the usual bold inside a math environment i.e.
don't $\textbf{y}$ --> use $\boldsymbol{y}$

* packages txfonts and amsmth collide in one command `\iid`. First load amsmth, then load out txfonts. 
https://groups.google.com/forum/#!topic/comp.text.tex/xldaN6CqLC4 . You cold

* using command \footnote inside a \caption{} environment : protect the command as \protect\footnote{foo}`

* 


