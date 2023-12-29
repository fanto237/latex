# Latex template for Essay and Thesis

This project is a fork of [Fabian Lignitz
]([https://](https://gitlab.informatik.hs-bremerhaven.de/flignitz/latex_vorlagen))'s latex template, which i modified to suit my needs.
It can be used to write essays as well as thesis such as Bachelor or Master thesis.
## Table of Contents
- [Latex template for Essay and Thesis](#latex-template-for-essay-and-thesis)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Install](#install)
    - [Run](#run)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)

## Installation
### Prerequisites
To use the template a latex compiler is required. There are several ones out there depending on the os you are using. I am a windows guy so i am using [Tex Live]([https://](https://www.tug.org/texlive/)), which also works on Mac and Linux. It is also possible to use another compiler such as [MikTex](https://miktex.org/), but you will also need to install **Perl**. \
You could also need a latex editor for convenience, since standard editors do not offer some useful tools like autocompletion or snippets. I personally use the [LaTeX-Workshop](https://github.com/James-Yu/LaTeX-Workshop/) extension for vs code, which is really helpful, when dealing with latex documents.

### Install
You can clone the project using git with the following command:
```console
git clone https://github.com/fantosama/latex.git
```
Or download the repo as a zip file and the unzip it.

### Run
To run the project (compile it), open the project directory and then run:
```console
latexmk main.tex
```
Or

```console
pdflatex  main.tex
```

depending on the cli-tool you have installed.
## Usage



## Contributing



## License

This project is licensed under the [MIT License](LICENSE).

