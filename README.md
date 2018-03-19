# tex-init

A modular LaTeX templete. (experimental)

## Workflow

### 1. Clone this repository

### 2. Edit config files

### 3. Write and organize contents

### 4. Compile

```
latexmk
```

## Design

* Semantic separation of document parts
* `main.tex` consists of `\input`
* Simple explanatory "docs" embedded in preambles
* (Tentative) Switchable modes, such as "lightweight" compiling with thrifty preambles, "full" compiling with rich preambles, figure-only compiling
* Internationalization

## Todo

* User-specific defaults as mixins
* Add beamer
* Enhance bibliogprahy bundle
* `texliveonfly`
* Think on dependency among bundles
* Add lightweight-compile mode
* Think about module-specific configurations

## Reference

* <http://id.fnshr.info/2017/05/20/my-latex-templates-201705/>
