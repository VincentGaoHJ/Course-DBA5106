# Course-DBA5106
Course Work for NUS MSBA DBA5106 2020

### assignment solution format

Fill the answers into the question jupyter notebook and run the result. After that, please download as pdf file.

- Compile ipynb file to tex

```
jupyter nbconvert --to latex yourNotebookName.ipynb
```

- Convert latex to pdf

```
xelatex yourNotebookName.tex
```

- If Chinese exists in the file, latex file needs to be amend manually

```
\usepackage{fontspec, xunicode, xltxtra}
\setmainfont{Microsoft YaHei}
```



*Also could use Markdown as intermediate file and convert it to PDF file using Typora*



### Some tips

- When using git to check some intermediate files generated by compiling tex, command below will give out all the ignored files in the whole repo (if you have some .git files suitable for it, it will also report them.)

```
find -type f | git check-ignore --stdin
```

