IceCube Internship Presentation
===
[Latest PDF Version](https://github.com/The-Ludwig/icecube-internship-presentation/releases/latest/download/icecube-internship-presentation.pdf)
[![Build LaTeX](https://github.com/The-Ludwig/icecube-internship-presentation/actions/workflows/build.yml/badge.svg)](https://github.com/The-Ludwig/icecube-internship-presentation/actions/workflows/build.yml)

I had an ~5-week internship at the IceCube working group in Stockholm. In this talk I summarized what I did.


# Building
To produce the output to `build/main.pdf` simply run
```sh
make
```

To use continuous building (i.e. while working on the document) use 
```sh
make work
```

# Beamer
You can also use this template to produce slides with `beamer`.
For that simply rename `main_beamer.tex` to `main.tex`. 
You can delete `header.tex` and the original `main.tex`. 

# Dependencies 
You need 
- texlive 
- make
