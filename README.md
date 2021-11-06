# template für die Fallstudie

installiert euch https://tug.org/texworks/#Getting_TeXworks

in VSCode die Extension https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop

Ich habe folgende settings verwendet.

	// latex
	"latex-workshop.docker.enabled": true,
	"latex-workshop.latex.outDir": "./out",
	"latex-workshop.synctex.afterBuild.enabled": true,
	"latex-workshop.view.pdf.viewer": "tab",
	"latex-workshop.docker.image.latex": "tianon/latex",
	// End
