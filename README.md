# Minimal Resume Template (LaTeX)

A dependency-light LaTeX resume template

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
