## NeurIPS 2019 Reproducibility Challenge [ReScience C](https://rescience.github.io/) Template

- Tracking issue: https://github.com/ReScience/NeurIPS-2019/issues/2

### [ReScience C](https://rescience.github.io/) article template

This repository contains a [copy of the Latex template](https://github.com/ReScience/template) for writing a ReScience
C article and the (mandatory) YAML metadata file.

#### Prerequisites

Install textlive 2019 in your system. If you are using Mac, easiest would be to install via HomeBrew:

```
brew cask install mactex
```

#### Usage

Fill in information in
[metadata.yaml](./metadata.yaml), modify [content.tex](content.tex)
and type:

```bash
$ make 
```

This will produce an `article.pdf` using xelatex and provided font.

**Note** : From the NeurIPS Latex format, copy all dependencies and add it in context.tex, _including the abstract_. 

As and when required, you'll need to complete [metadata.yaml](./metadata.yaml) with information provided by the editor and type again:

```bash
$ make
```

