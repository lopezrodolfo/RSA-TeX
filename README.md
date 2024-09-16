# RSA with Abstract Algebra

This project contains a LaTeX document `main.tex` for typesetting.

## Author

Rodolfo Lopez

## Date

May 2022

## Setup (macOS)

1. Install BasicTeX:

   ```
   brew install basictex
   ```

2. Add BasicTeX to PATH:

   ```
   echo 'export PATH="/Library/TeX/texbin:$PATH"' >> ~/.zshrc
   source ~/.zshrc
   ```

3. Install latexmk:
   ```
   sudo tlmgr update --self
   sudo tlmgr install latexmk
   ```

## Usage

To compile the document, run:

```
latexmk -pdf main.tex
```

This will generate a `main.pdf` of the LaTeX document.
