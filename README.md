# URPP Tutorials
## URPP Evolution in Action

![URPP logo](Logo_URPP.png)

Stefan Wyder & Heidi Lischer



## Introduction to git

The tutorial is heavily based on a [Software Carpentry Course](http://swcarpentry.github.io/git-novice/)  
  
  
1. Introduction
2. [Setting Up Git](http://swcarpentry.github.io/git-novice/02-setup.html)
3. [Creating a Repository](http://swcarpentry.github.io/git-novice/03-create.html)
4. [Tracking Changes](http://swcarpentry.github.io/git-novice/04-changes.html)
5. [Exploring History](http://swcarpentry.github.io/git-novice/05-history.html)
6. [Ignoring Things](http://swcarpentry.github.io/git-novice/06-ignore.html)
7. Remotes in GitHub
8. Collaborating
9. Conflicts
10. Open Science
11. Licensing
12. Hosting


Chapters 1-6 by Stefan  
Chapters 7-12 by Heidi ([PDF Presentation](Exercises_Git_Tutorial_HL.pdf) | [PDF Exercises](Exercises_Git_Tutorial_HL.pdf) )
Chapters 13-16 by Stefan  

check also http://swcarpentry.github.io/git-novice/instructors.html



13. [Large files](https://git-lfs.github.com/) [Video (2min)](https://www.youtube.com/watch?v=uLR1RNqJ1Mw)
14. Non-text files
Many people want to version control non-text files, such as images, PDFs and Microsoft Office or LibreOffice documents. It is true that Git can handle these filetypes (which fall under the banner of “binary” file types)

Much of Git’s magic comes from being able to do line-by-line comparisons (“diffs”) between files. This is generally easy for programming source code and marked up text. For non-text files, a diff can usually only detect that the files have changed but can’t say how or where.

[Support for pictures](https://help.github.com/articles/rendering-and-diffing-images/)

git diff --word-diff is very handy for csc, tex mkd, 
Compare tables: https://paulfitz.github.io/daff

15. Website hosting
The README file is what’s generally shown by default in this view of a repository, and standard to have in your GitHub project. It’s basically just a text file that supports the Markdown syntax
16. Best practices

Ideally, each commit should be minimal but complete:

Minimal: A commit should only contain changes related to a single problem. This will make it easier to understand the commit at a glance, and to describe it with a simple message. If you should discover a new problem, you should do a separate commit.

Complete: A commit should solve the problem that it claims to solve. If you think you’ve fixed a bug, the commit should contain a unit test that confirms you’re right.

Each commit message should:

Be concise, yet evocative. At a glance, you should be able to see what a commit does. But there should be enough detail so you can remember (and understand) what was done.

Describe the why, not the what. Since you can always retrieve the diff associated with a commit, the message doesn’t need to say exactly what changed. Instead it should provide a high-level summary that focuses on the reasons for the change.




### The problem

- "The final version" from [PHD comics](http://www.phdcomics.com/comics/archive.php?comicid=1531)
<img src="finalDoc.gif" width="300">

- You want to improve a working script. After 2 hours of rewriting the new script still doesn't work. Unfortunately you overwrote
the original version that worked and can't go back. 

- Which version did I use 3 years ago when I did the analysis?


### The solution: versioning

Git/Github is increasingly used to handle research outputs such as datasets, statistical code, figures, lab notes, and manuscripts.
Git can be used to increase reproducibility, as a backup system against data loss, for facilitating collaboration or simply
if you are working on several computers. 

- giant undo button
- collaboration - several people working on the same documents
- backup system against data loss
  you can retrieve and compare versions
- increase reproducibility
- you work on multiple computers  


Git is just one popular versioning system. 

Git is complicated and Learning git (and using) is sometimes frustrating.  
"Git has a real knack for making me feel stupid!" Torsten Seemann


### Installing git on the command line

In my opinion it is easier to learn git using the command line. After initial setup all we need for our daily work are 2 or 3 git commands -
With time we learn and memorize more commands. 
By using graphical interfaces there is a higher risk of using advanced commands without really knowing what they do.  
  
- Mac
  Install Git from here: http://git-scm.com/downloads.  
  For older versions of OS X (10.5-10.7) use the most recent available installer available [here](https://code.google.com/p/git-osx-installer/downloads/list).
- Windows
  Install Git for Windows by downloading and running [the installer](http://msysgit.github.io/). This will provide you with both Git and Bash in the Git Bash program.
- Linux
  You can install it via your distribution's package manager. For Ubuntu run `sudo apt-get install git`.


### Installing Graphical Interfaces

We recommend [SourceTree (Mac, Windows)](https://www.sourcetreeapp.com/), [Github for Mac](https://mac.github.com/) and, for Linux, [SmartGit](http://www.syntevo.com/smartgit/.)
  
RStudio also comprises a basic git client.  
  
Because all of the clients are just forming and executing Git commands on your behalf, you don’t have to pick one.  
You can literally do one operation from the command line, do another from RStudio, and another from SourceTree, one after the other, and it just works.

For a full list of available software, see http://git-scm.com/downloads/guis


### Installation problems

In case of installation problems, consult [this site](http://stat545-ubc.github.io/git01_git-install.html) and [this site](http://ttimbers.github.io/2015-04-30-SFU/).


### Setting up git

Configure git the first time is used on a computer.    
  
Tell Git your name so your commits will be properly labeled
```
git config --global user.name "YOUR NAME"
```

Tell Git the email address that will be associated with your Git commits.
```
git config --global user.email "YOUR EMAIL ADDRESS"
```

[Github help](https://help.github.com/articles/set-up-git/)
http://swcarpentry.github.io/git-novice/02-setup.html


### Getting help

- https://help.github.com/
- https://help.github.com/articles/good-resources-for-learning-git-and-github/
- https://www.atlassian.com/git/
- http://gitimmersion.com/


### Links

*Cheatsheets*
- [Cheatsheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)
http://swcarpentry.github.io/git-novice/reference.html
- [Git Reference (Software-Carpentry)](http://software-carpentry.org/v5/novice/ref/02-git.html)

*Courses*
- [Interactive learning git (15 minutes)](https://try.github.io/levels/1/challenges/1)
- [Interactive learning](http://pcottle.github.io/learnGitBranching/)
- [Software Carpentry Course](http://swcarpentry.github.io/git-novice/)

- [Git book](http://git-scm.com/book/en/v2)

*Markdown*
- [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Markdown basics](https://help.github.com/articles/markdown-basics/)
- [Writing on github](https://help.github.com/articles/writing-on-github/)


### Tips

- Graphical diff/merge software, e.g. [DiffMerge](https://sourcegear.com/diffmerge/) 



First aid git (most frequently asked git questions)
http://firstaidgit.io/#/
http://thelinell.com/2014/12/23/curated-git-links-of-2014/
http://41j.com/blog/2015/02/common-git-screwupsquestions-solutions/?utm_content=bufferfbdd4&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer

How to undo (almost) anything with Git
https://github.com/blog/2019-how-to-undo-almost-anything-with-git

graph: undoing changes
https://twitter.com/emmajanehw/status/549919920990208000
