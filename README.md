# Research Project Template

This is my starting template for a research project. I have it set up with a single `ANALYSIS` directory, although this can be easily be changed. All raw data goes into the `ANALYSIS/input` directory and all results or constructed data goes into the `analysis/output` directory. All programs should be logged when possible and should go in `ANALYSIS/logs`. All scripts and programs should typically go in the main directory. Often I will also put in a bash shell script that clarifies the order and organization of these files.

The `PAPER` directory contains more files in the basic template. The `main.Rmd` file is for the main body of the paper and this will utilize the `project.bib` bibtex file (typically saved from a group constructed in Zotero) and template files from the `templates` directory. Tables and figures go into a separate file in `addenda/tablesfigs.Rmd`. If required, an appendix can be added with `addenda/appdendix.Rmd`. The file `combinepdfs.sh` will combine the pdfs of the main body, the tables and figures, and the appendices into a single pdf. The pagenumber characteristic in the YAML header of the `tablesfigs.Rmd` and `appendix.Rmd` can be adjusted manually to keep the pagination correct.

To start a new project, copy and paste contents to a new directory. 
