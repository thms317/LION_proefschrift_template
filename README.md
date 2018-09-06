# LION_proefschrift_template
This template for the _Fysica van Leven_ PhD theses at _Leiden Universiteit_. 
This is nothing official, I (Patrick) just set this up since there was nothing out there.
The template is based on Hedde's PhD thesis, which in turn was based on Stefan's.

## How to
Download this repository and construct a PDF file as minimum working example (MWE).

### Downloading the repo
Click the download button at the top right of  or in shell run:

```bash
cd ~
wget https://github.com/patrickvdb/LION_proefschrift_template/archive/master.zip
unzip master.zip
rm master.zip
```

### Compiling the MWE
This works in Mac terminal, I don't know how you would run this on a Windows computer. 
```bash
cd ~/LION_proefschrift_template-master # change directory to the folder 

pdflatex proefschrift.tex # compiles, but without table of contents
biber proefschrift.bcf # add table of contents
pdflatex proefschrift.tex # compile again, this time with toc
```