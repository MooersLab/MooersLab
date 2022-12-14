# MooersLab

This site contains the public repositories of the Dr. Blaine Mooers Lab, Department of Biochemistry and Molecular Biology, College of Medicine, University of Oklahoma Health Sciences Center, Oklahoma City, Oklahoma, USA.
My lab determines the structures of biomolecular molecules and their complexes with drugs using mostly [X-ray crystallography](https://en.wikipedia.org/wiki/X-ray_crystallography#Biological_macromolecular_crystallography) and sometimes [small angle X-ray scattering](https://en.wikipedia.org/wiki/Small-angle_X-ray_scattering), a method that does not require crystals. 
We grow crytals using advanced experimental design methods and collect X-ray diffraction data inhouse and frequently at the [Stanford Synchrotron Radiation LightSource](https://www-ssrl.slac.stanford.edu/content/) and sometimes at the four other major LightSources in the US.
We also do structure-based drug design using supercomputers.

We are not computer scientists, but we do write a little code.
We have made some software tools to ease the writing of PyMOL scrpts for making molecular images.
These tools are available for the top 20 text editors and Jupyter and Colab notebooks. 

<!--
(PS The ultimate text editor for writing prose and code is Emacs.
All paths through text editors lead to Emacs.
Some people get stuck all too long in Vim or NeoVim, which are great editors.)
-->

# Index of repositories

## ACA talks
- [ACA2021](https://github.com/MooersLab/ACA2021)
- [ACA2022](https://github.com/MooersLab/ACA2022)

## Bash related
- [Bash functions for Schooner at OSCER](https://github.com/MooersLab/bashFunctions4oscer)
- [Multiple file transfer](https://github.com/MooersLab/multipleFileTransfer)

## Bayeisan Data Analysis
- [JointProb](https://github.com/MooersLab/jointprob1D) Rmarkdown and jupyer notebooks for the JointProb study group.

## Blog
- [Lab website with blog posts](https://mooerslab.github.io/year-archive/)


## Crystallographic computing
- [Jupyterlab cctbx snippets](https://github.com/MooersLab/jupyterlabcctbxsnips) CCTBX snippets for JupyterLab with the jupyterlab-snippets extension or the jupyterlab-snippets-mutlimenus extension.
- [Colab cctbx snippets](https://github.com/MooersLab/colabcctbxsnips) Colab snippets.

## Emacs related
- [crafted-emacs user config](https://github.com/MooersLab/crafted-emacs-config) My user configuration file (config.el) for the crafted-emacs profile. I did install use-package and used it to install several packages. The base profile has the Doom theme, Vertico completion stack, and eglot. I added my org-agenda config and my favorite key bindings. I am currently *luvin* it. 
- [latex-emacs configuration](https://github.com/MooersLab/latex-emacs) A configuration file enhancing the use of LaTeX in Gnu Emacs. Includes org-mode configuration.
- [latex-emacs28 configuration](https://github.com/MooersLab/latexemacs28/blob/main/README.md) Similar to above but for Gnu Emacs version 28.
- [scimax user.el](https://github.com/MooersLab/scimax) Scimax is the Emacs configuration that John Kitchin is developing to support reproducible research by scientists with Gnu Emacs. The *user.el* file for scimax enables scimax users to add keybindings and packages. I added features from latex-emacs and config.org.
- [config.org](https://github.com/MooersLab/config) My default configuration file for GNU Emacs version 30.
- [Writing log template in Org-mode](https://github.com/MooersLab/writingLogTemplateInOrg) Template for tracking your actions, decisions, and plans for any serious writing project that takes more than one session to finish. The LaTeX version is listed in the LaTeX section for use on Overleaf or in Emacs.
- [Org-mode manuscript template](https://github.com/MooersLab/manuscriptInOrg/edit/main/README.md) The manuscript will be exported to PDF after being run through LaTeX. This is for the first submission. This is for the lovers of org-mode. The export from org to PDF is fast and painless in Emacs.
- [Slides about workflow in LaTeX](https://github.com/MooersLab/BerlinEmacsAugust2022) presented to the Berlin Emacs Meetup August 2022. Not recorded. It was a 90-minute presentation.
- [snippets for latex-mode in Emacs](https://github.com/MooersLab/snippet-latex-mode) My LaTeX code snippets for yasnippets.
- [Quizzes about Emacs to improve recall of keybindings](https://github.com/MooersLab/qemacs) Ten minutes boosting your recall on a particular topic can save 10, 100, or 1000 hours of Google searches, espcially if you are prone to getting side-tracked in the Google-verse.
- [Slides from talk about GhostText, Data Science Workshop, July 2022](https://github.com/MooersLab/DSW22ghosttext) GhostTexT rocks! It enables the editing of textboxes on web sites with Emacs. You can use GhostText to bring the full power of Emacs to Overleaf (*Important:*  use the legacy version rendering of the text area in Overleaf to get text impoted into a LaTeX buffer).
- [Video link to talk about GhostText, Oklahoma Data Science Workshop, July 2022](https://mediasite.ouhsc.edu/Mediasite/Channel/python/watch/4da0872f028c4255ae12935655e911321d)
- [emacsconf 2021 talk about rendering molecular graphics with PyMOL in org literate programming files](https://emacsconf.org/2021/talks/molecular/)
- [emacsconf 2022 talk about using Emacs to edit Jupyter cells via GhostText and atomic-chrome](https://emacsconf.org/2022/talks/jupyter/)

## LaTeX related
Note that I currently write alot in Emacs on 750words.com via GhostText. I configured atomicchrome to go to LaTeX mode when GhostText connects to 750words. I can also use Emacs to write and edit text in Overleaf via atomicchrome and GhostText.
This is a very cool way of extending Emacs to websites with weaker editors.

- [latex-emacs](https://github.com/MooersLab/latex-emacs) A configuration file supporting the use of LaTeX in Emacs.
- [Slides about workflow in LaTeX](https://github.com/MooersLab/BerlinEmacsAugust2022) presented to the Berlin Emacs Meetup August 2022. Not recorded. It was 90-minute lecture.
- [slideshowTemplateInLaTeX](https://github.com/MooersLab/slideshowTemplateLaTeX) Slideshow template in Beamer makes slides that do not look like they were made in LaTeX.
- [posterInLaTeX](https://github.com/MooersLab/posterInLaTeX) Uses beamer to make a poster via a simple design. Enables whipping together a poster a few hours. It is much easier than using powerpoint.
- [LaTeX manuscript template](https://github.com/MooersLab/manuscriptInLaTeX/edit/main/README.md) Generic template for the first submission as a PDF.
- [Writing log template in LaTeX](https://github.com/MooersLab/writingLogTemplate) Place to track progress and plans behind a manuscript.
- [Annotated bibliography Template in LaTeX](https://github.com/MooersLab/annotatedBibliography) Every writing project needs one of these.
- [Diary for 2022 in LaTeX](https://github.com/MooersLab/diary2022inLaTeX) Each day is a section. Each month is a chapter. Has an index (something that some markdowns cannot generate). Very feature-rich and ready to use.
- [Diary for 2023 in LaTeX](https://github.com/MooersLab/diary2023inLaTeX) Same as above but reformatted for 2023
- [snippets for latex-mode in Emacs](https://github.com/MooersLab/snippet-latex-mode) My LaTeX code snippets for yasnippets.
- [The writer's creed](https://github.com/MooersLab/thewriterslaw) Guidelines for greater productivity.


## Molecular Graphics related

#### PyMOL
- [pymolrc](https://github.com/MooersLab/pymolrc) My pymolrc file.
- [pymolsnips](https://github.com/MooersLab/pymolsnips) Contains extensive instructions on installing 19 text editors.
- [pymolshortcuts](https://github.com/MooersLab/pymolshortcuts) Very useful for non-coders.
- [EasyPyMOL](https://github.com/MooersLab/EasyPyMOL) Support for horizontal scripting.
- [orgpymolpysnips](https://github.com/MooersLab/orgpymolpysnips) Support for literate programming in org-mode with PyMOL.
- [rstudiopymolpysnips](https://github.com/MooersLab/rstudiopymolpysnips) Support for literate programming in Rstuido with PyMOL.
- [taggedpymolpysnips](https://github.com/MooersLab/taggedpymolpysnips) Support for literate programming in JupyterLab with tagged snippets with the elyra-snippets extension and with PyMOL.
- [jupyterlabpymolpysnips](https://github.com/MooersLab/jupyterlabpymolpysnips) PyMOL Python snippets for use in JupyterLab with the jupyterlab-snippets extension.
- [colabOpenSourcePyMOLpySnips](https://github.com/MooersLab/colabOpenSourcePyMOLpySnips) PyMOL Python snippets for use in Colab with open source PyMOL.
- [colabPyMOLpySnips](https://github.com/MooersLab/colabPyMOLpySnips) PyMOL Python snippets for use in Colab with the incentive PyMOL.
- [PyMOL wall hangings](https://github.com/MooersLab/PyMOLwallhangings) Protocol for making oversized images to be framed and hung on the wall.
<!--
## Structure-based Drug Design
-->



## Supercomputing related (includes HPC, cluster computing, cloud computing)
- [Bash functions for Schooner at OSCER](https://github.com/MooersLab/bashFunctions4oscer)
- [Emacs configuration file for schooner supercomputer](https://github.com/MooersLab/emacs4oscer)
- [Multiple file transfer](https://github.com/MooersLab/multipleFileTransfer)
- [Vim configuration file for schooner supercomputer](https://github.com/MooersLab/vimrc4oscer) 
- [Vim configuration file for SSRL SMB cluster](https://github.com/MooersLab/vimrc4ssrl)
- [Tutorial for biologists on using the supercomputer at OU-Norman](https://github.com/MooersLab/oscer-supercomputer-tutorial)


## Vim (and Neovim)
- [Vim configuration file](https://github.com/MooersLab/vimrc) Current vimrc file for Mac OSX 10.15
- [Vim configuration file for schooner supercomputer](https://github.com/MooersLab/vimrc4oscer) 
- [Vim configuration file for SSRL SMB cluster](https://github.com/MooersLab/vimrc4ssrl)
- [Neovim configuration file](https://github.com/MooersLab/neovim-init-file)
- [qvim](https://github.com/MooersLab/qvim) Quiz about Vim commands to improve your recall of the commands after a break from using Vim.

**MooersLab/MooersLab** is a ??? _special_ ??? repository because its `README.md` (this file) appears on his GitHub profile ????.

<!--

Here are some ideas to get you started:

- ???? I???m currently working on ...
- ???? I???m currently learning ...
- ???? I???m looking to collaborate on ...
- ???? I???m looking for help with ...
- ???? Ask me about ...
- ???? How to reach me: ...
- ???? Pronouns: ...
- ??? Fun fact: ...
- ????
-->
