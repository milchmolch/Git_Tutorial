# URPP Tutorials
## URPP Evolution in Action

![URPP logo](Logo_URPP.png)

Stefan Wyder & Heidi Lischer



## Introduction to git

The tutorial is heavily based on a [Software Carpentry Course](http://swcarpentry.github.io/git-novice/)  
  
  
1. Introduction
2. [Setting Up Git](http://swcarpentry.github.io/git-novice/02-setup)
3. [Creating a Repository](http://swcarpentry.github.io/git-novice/03-create)
4. [Tracking Changes](http://swcarpentry.github.io/git-novice/04-changes)
5. [Exploring History](http://swcarpentry.github.io/git-novice/05-history)
6. [Ignoring Things](http://swcarpentry.github.io/git-novice/06-ignore)
7. Remotes in GitHub
8. Collaborating
9. Conflicts
10. Open Science
11. Licensing
12. Hosting


Chapters 1-6 by Stefan  
Chapters 7-12 by Heidi ([PDF Presentation](URPP_Tutorial_Git_HL.pdf) | [PDF Exercises](Exercises_Git_Tutorial_HL.pdf))  
  

[Course Summary with Glossary](http://swcarpentry.github.io/git-novice/reference)  
  
  
**Additional topics (Stefan)**  

 13. [Non-code files (Images, PDFs, Office documents)](NonCodeFiles.md)
 14. Large files  [Link1](https://about.gitlab.com/2017/01/30/getting-started-with-git-lfs-tutorial/) | [Link2](https://git-lfs.github.com/) | [Video (2min)](https://www.youtube.com/watch?v=uLR1RNqJ1Mw)
 15. [Documentation/Website hosting](Documentation.md)
 16. [Commit best practices](http://r-pkgs.had.co.nz/git.html#commit-best-practices)


### Installing git on the command line

In my opinion it is easier to learn git using the command line. After initial setup all we need for our daily work are 3 or 4 git commands -
with time we learn and memorize more commands. 
By using graphical interfaces there is a higher risk of using advanced commands without really knowing what they do.  
  
- Mac  
  Install Git from here: http://git-scm.com/downloads.  
  For older versions of OS X (10.5-10.7) use the most recent available installer available [here](https://code.google.com/p/git-osx-installer/downloads/list).
- Windows  
  Install Git for Windows by downloading and running [the installer](http://msysgit.github.io/). This will provide you with both Git and Bash in the Git Bash program.
- Linux  
  You can install it via your distribution's package manager. For Ubuntu run `sudo apt-get install git`.


### Installing Graphical Interfaces

We recommend [SourceTree (Mac, Windows)](https://www.sourcetreeapp.com/), [Github for Mac](https://mac.github.com/) and, for Linux, [gitkraken](https://www.gitkraken.com/) or [SmartGit](http://www.syntevo.com/smartgit/).
  
RStudio also comprises a basic git client.  
  
Because all of the clients are just forming and executing Git commands on your behalf, you don’t have to pick one.  
You can literally do one operation from the command line, do another from RStudio, and another from SourceTree, one after the other, and it just works.

For a full list of available graphical interfaces, see http://git-scm.com/downloads/guis


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

[set-up help](https://help.github.com/articles/set-up-git/) | [other link](http://swcarpentry.github.io/git-novice/02-setup)


### Getting help

- https://help.github.com/
- https://help.github.com/articles/good-resources-for-learning-git-and-github/
- https://www.atlassian.com/git/
- [Stackoverflow](http://stackoverflow.com)


### Links

**Cheatsheets**
- [Simple cheatsheet](http://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf)
- [Longer Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [Git Reference (Software-Carpentry)](http://software-carpentry.org/v5/novice/ref/02-git)

**Courses**
- http://gitimmersion.com/
- [Interactive learning git (15 minutes)](https://try.github.io/levels/1/challenges/1)
- [Git - the simple guide](http://rogerdudler.github.io/git-guide/)
- [Happy Git and GitHub for R useRs](http://happygitwithr.com/)
- [Interactive learning](http://pcottle.github.io/learnGitBranching/)
- [Software Carpentry Course](http://swcarpentry.github.io/git-novice/)  
  
- [Git book](http://git-scm.com/book/en/v2)

**Improving git skills**  
- https://github.com/GitInPractice/GitInPractice
- http://firstaidgit.io/#/
- http://thelinell.com/2014/12/23/curated-git-links-of-2014/
- http://41j.com/blog/2015/02/common-git-screwupsquestions-solutions/

**How to undo (almost) anything with Git**  
- https://github.com/blog/2019-how-to-undo-almost-anything-with-git
- [Graph](https://twitter.com/emmajanehw/status/549919920990208000)

**Markdown**  
- [tutorial with step-by-step interactive exercises](http://commonmark.org/help/tutorial/)

### Tips

- Graphical diff/merge software, e.g. [DiffMerge](https://sourcegear.com/diffmerge/) 
- Github gives educational discounts to students, teachers, administrators, and researchers. Apply at https://education.github.com
- [Git in science](http://www.scfbm.org/content/8/1/7)
