## Non-code files

Many people want to version control non-text files, such as images, PDFs and Microsoft Office or LibreOffice documents. Git can non handle well 
these filetypes (which are "binary" file types).

Much of Git’s magic comes from being able to do line-by-line comparisons ("diffs") between files. This is generally easy for programming
source code and Markdown text. For non-text files, a diff can usually only detect that the files have changed but can’t say how or where.  
  
However, Github supports diffing Markdown text ([see 1 example](https://github.com/milchmolch/Git_Tutorial/commit/10fa03d86e4f7a9a09cf48a08e84efde96473bda?diff=split#diff-04c6e90faac2675aa89e2176d2eec7d8)) and even [images](https://help.github.com/articles/rendering-and-diffing-images/) (including PNG, JPG, GIF, PSD and SVG) 
With tricks we can also [compare tables](https://paulfitz.github.io/daff).

    
Github offer special handling for and renders PDF documents, PNG & SVG images, tabular data (csv,tsv), Markdown, AsciiDoc, Jupyter Notebook (ipynb) and some less common
formats (see [this help page](https://help.github.com/categories/working-with-non-code-files)).   
  
  
In general, I include PDF files and Office documents under version control only if they change rarely.   
  
    
**Tip**     
`git diff --word-diff` is very handy for csc, Latex, markdown files.
