# Thème Latex UNamur
Auteur: Antoine Jacques
Faculté d'informatique, UNamur

## Arborescence
```
.
├── figures
│   └── README.md
├── page_de_garde
│   ├── logo
│   │   └── logo.png
│   ├── config.tex
│   ├── maketitle.tex
│   └── README.md
├── preambule
│   ├── preambule.tex
│   └── README.md
├── scripts
│   └── README.md
├── section
│   └── README.md
├── main.tex
└── README.md
```

## Utilisation du template

La compilation se fait par le fichier preambule/preambule.tex. Ce fichier comprend tous les packages que j'utilise régulièrement ainsi que leur configuration.
Le fichier main.tex pourra être organisé comme ceci: 
```xml
\begin{document}
\maketitle
\tableofcontents
\newpage
\section{Nom de la section 1}
	\input{section/section1.tex}
	% \newpage
\section{Nom de la section 2}
	\input{section/section.tex}
	% \newpage
...
\end{document}
```

Cette manière de travailler permet de ne pas se perdre dans ses documents latex.
## TODO
- [ ] Automatiser les références bibliographiques
