## Non-code files

Many people want to version control non-text files, such as images, PDFs and Microsoft Office or LibreOffice documents. Git can handle 
these filetypes (which are  "binary" file types).

Much of Git’s magic comes from being able to do line-by-line comparisons ("diffs") between files. This is generally easy for programming
source code and Markdown text. For non-text files, a diff can usually only detect that the files have changed but can’t say how or where.  
  
However, Github supports diffing Markdown text ([1 example]()) and even [images](https://help.github.com/articles/rendering-and-diffing-images/) (including PNG, JPG, GIF, PSD and SVG) 
With tricks we can also [compare tables](https://paulfitz.github.io/daff).

    
Github in-browser renders PDF documents, tabular data (csv,tsv), Markdown, AsciiDoc and some less common
formats (see [this help page](https://help.github.com/categories/working-with-non-code-files))  
  
  
In general, I include PDF files and Office documents under version control only if they change rarely.   
  
    
**Tip**     
`git diff --word-diff` is very handy for csc, Latex, markdown files.
