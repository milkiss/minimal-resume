# Minimal Resume Template (LaTeX)

A dependency-light LaTeX resume template

## Preview

[![Resume preview](https://raw.githubusercontent.com/milkiss/minimal-resume/master/resume.png)](https://raw.githubusercontent.com/milkiss/minimal-resume/master/resume.pdf)

## Installation

For macOS users, the simplest setup is with **BasicTeX**:

```bash
brew install basictex
```

Then, install the minimal packages (if not already present):

```bash
sudo tlmgr update --self
sudo tlmgr install geometry hyperref lmodern
```

## Usage

```bash
pdflatex resume.tex
```

Output: resume.pdf
