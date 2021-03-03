# CV

Here you can find my current CV

## Dependenies

You need to have the following latex modules installed

* texlive-scheme-basic 
* texlive-moderncv
* texlive-ec
* texlive-fontawesome5
* texlive-changebar
* latexmk

```
dnf install texlive-scheme-basic texlive-moderncv texlive-ec texlive-fontawesome5 texlive-changebar latexmk
```

## Build

To build, simply execute

```
latexmk
```

### Alternative: Build manually with `pdflatex`
If you prefer the manual way, you need to execute

```
# Create build directory
mkdir build

# English:
pdflatex -output-directory build carle_en.tex 

# German:
pdflatex -output-directory build carle_de.tex 
```

## Generated PDFs

After build, there will be two PDFs:
* `./build/carle_en.pdf` --- the English CV
* `./build/carle_de.pdf` --- the German CV