![Version](https://img.shields.io/static/v1?label=mooerslab&message=0.5&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

# MooersLab

## Quick Links

- [bash](https://github.com/MooersLab#bash-related)
- [cctbx](https://github.com/MooersLab#cctbx-related)
- [Emacs](https://github.com/MooersLab#emacs-related)
- [Experimental designs](https://github.com/MooersLab#experimental-designs)
- [Jupyter and Colab](https://github.com/MooersLab#jupyter-and-colab-related)
- [LaTeX](https://github.com/MooersLab#latex-related)
- [PyMOL](https://github.com/MooersLab#pymol)
- [SAXS](https://github.com/MooersLab#small-angle-scattering)
- [Supercomputing](https://github.com/MooersLab#supercomputing-related)
- [vim/neovim](https://github.com/MooersLab/MooersLab/blob/main/README.md#vim-and-neovim)
- [Writing tools](https://github.com/MooersLab#writing-productivity-tools)
- [Voice computing](https://github.com/MooersLab#voice-computing)
- [Videos of talks](https://github.com/MooersLab#videos-related-to-these-repos)


## Introduction
This site contains the public repositories of the Dr. Blaine Mooers Lab, Department of Biochemistry and Physiology, College of Medicine, University of Oklahoma Health Sciences, Oklahoma City, Oklahoma, USA.
My lab determines the structures of biological macromolecules and their complexes with drugs, mainly using [X-ray crystallography](https://en.wikipedia.org/wiki/X-ray_crystallography#Biological_macromolecular_crystallography) and sometimes small-angle[ X-ray scattering](https://en.wikipedia.org/wiki/Small-angle_X-ray_scattering)](https://en.wikipedia.org/wiki/Small-angle_X-ray_scattering), a method that does not require crystals.
We grow crystals using advanced experimental design methods and collect X-ray diffraction data in-house and frequently at the [Stanford Synchrotron Radiation LightSource](https://www-ssrl.slac.stanford.edu/content/) and sometimes at the four other significant light sources in the US.
We also do structure-based drug design using supercomputers.

We are not computer scientists; we leave the heavy-duty coding to the professionals.
However, we write code occasionally to help advance our science and the science of others.
We have developed software tools to ease the writing of PyMOL scripts to make molecular images.
These tools are available for the top 19 text editors and the Jupyter, Colab, and R Markdown notebooks.
These text editors can make your work lighter and have many wonderful features, but Emacs is our favorite because, thanks to Emacs Lisp, it is the most customizable text editor.
However, we caution that one must take a disciplined approach to Emacs, a tinker's paradise.

We often use the web service called *Overleaf* to write manuscripts, grant applications, slideshows, posters, and lab notebooks in LaTeX.
We spent five years trying the alternative Markup languages.
This was before I became aware of Overleaf, which made working with LaTeX much easier.
Some of our LaTeX templates are in the repositories found here (see the section on [LaTeX](https://github.com/MooersLab#latex-related) below).

Overleaf is a great way to get started with LaTeX.
However, Emacs provides access to more powerful editing features.
You can use GhostText to send a page from Overleaf to Emacs for editing.
Nonetheless, Overleaf is great for collaborative writing. 
When using Chrome or Microsoft Edge, you can use the Voice In plugin for Google Chrome to dictate prose in Overleaf.

We are also fans of Jupyter Notebooks.
Something inexplicable about Jupyter Notebooks makes coding in them fun.
We have developed tools for working on Jupyter with PyMOL and CCTBX.
Jupyter Notebooks may be frustrating for those without at least some formal training in computing.
You must always be aware of your computer's state, or at least the state you expected it to be in.
Those who lack this awareness will run into a lot of trouble.

We also like R Markdown notebooks.
Although somewhat less interactive than Jupyter notebooks, these are simpler to put under version control, and they support custom libraries of code snippets with tab triggers and tab stops.
The RStudio IDE provides excellent support for R Markdown notebooks.
You can have the best of both worlds by editing R Markdown notebooks in Emacs and using the reticulate package to harness Jupyter kernels to run Python inside the notebook.

We code in mainly in Python but sometimes in Bash, R, Clojure, Elisp, Julia, Fortran, and C/C++.
It is hard to be a polyglot programmer due to limitations on mental bandwidth.

Our repositories are grouped by category.
Some repositories are listed in several categories.
This listing is still a work in progress.
Some repositories still need to be added to this page.
Seventeen repos are forks to other people's repositories.
Visit the [repositories tab](https://github.com/MooersLab?tab=repositories) to see the complete list of repositories.

In the spring of 2023, I started a [MooersLab](https://codeberg.org/MooersLab) site on Codeberg.
A foundation runs Codeberg and has 13 years of funding.
Some repositories on GitHub get mirrored on Codeberg.

If you like a repository, please click on the star in the upper right.

<!--
(PS The ultimate text editor for writing prose and code is Emacs.
All paths through text editors lead to Emacs.
Some people get stuck all too long in Vim or NeoVim, which are great editors.)
-->

# Index of repositories

## ACA talks
- [ACA2021](https://github.com/MooersLab/ACA2021)
- [ACA2022](https://github.com/MooersLab/ACA2022)
- [ACA2023](https://github.com/MooersLab/dsd4xtals)

## Bash related
- [Bash functions for Schooner at OSCER](https://github.com/MooersLab/bashFunctions4oscer)
- [Multiple file transfer](https://github.com/MooersLab/multipleFileTransfer)
- [Function that counts lines of uncommented code](https://github.com/MooersLab/count-lines-of-code/tree/main)

## Bayesian Data Analysis
- [Bayesian Data Analysis (BDA) Speech-to-Text expansions of acronyms](https://github.com/MooersLab/bayesian-data-analysis-voice-in/blob/main/README.md)
- [JointProb](https://github.com/MooersLab/jointprob1D) R Markdown and Jupyter notebooks for the Saturday JointProb study group that was active in 2022 and 2023.

## Blog
- [Lab website with blog posts](https://mooerslab.github.io/year-archive/)

## Clojure
- [ClojConj 2023 talk about protein structure superposition via probabilistic programming in Clojure](https://www.youtube.com/watch?v=lDweOPGHLB8&t=51s)
- [quizzes about Clojure](https://github.com/MooersLab/qclj) These quizzes are useful for improving command recall after a break in using Clojure for several months.


## Crystallographic computing

### CCTBX related

<a id="cctbxsnips-for-notebooks"><h4>For use in notebooks</h4></a>

- [Jupyterlab cctbx snippets](https://github.com/MooersLab/jupyterlabcctbxsnips) CCTBX snippets for JupyterLab with the *jupyterlab-snippets* extension or the jupyterlab-snippets-mutlimenus extension.
- [Jupyterlab cctbx plus snippets](https://github.com/MooersLab/jupyterlabcctbxsnipsplus) The variant of the *jupyterlabcctbxsnips* library with comments to guide editing of the snippets.
- [Tagged cctbx snippets](https://github.com/MooersLab/taggedcctbxsnips) The variant for the Elyra-snippet extension for Jupyterlab. The snippets have tags in their metadata that can be used to retrieve code snippets.
- [Tagged cctbx plus snippets](https://github.com/MooersLab/taggedcctbxsnipsplus) The variant for the Elyra-snippet extension for Jupyterlab. The tab stops in a comment block to guide the editing of the live snippet. The snippets have tags in their metadata that can be used to retrieve snippets.
- [Colab cctbx snippets](https://github.com/MooersLab/colabcctbxsnips) Colab snippets.


<a id="cctbxsnips-for-editors"><h4>For use in text editors</h4></a>

- [cctbxsnips-Emacs](https://github.com/MooersLab/cctbxsnips-Emacs) CCTBX snippets for the *yasnippet* snippet system in for Emacs.
- [cctbxsnips-SublimeText3](https://github.com/MooersLab/cctbxsnips-SublimeText3) CCTBX snippets for Sublime Text 3 (ST3).
- [cctbxsnips-VSC](https://github.com/MooersLab/cctbxsnips-VSC) CCTBX snippets for Visual Studio Code (VSC).
- [cctbxsnips-UltiSnips](https://github.com/MooersLab/cctbxsnips-Ultisnips) CCTBX snippets for Vim or NeoVim via UltiSnips plugin.
- [cctbxsnips-neosnippets](https://github.com/MooersLab/cctbxsnips-neosnippets) CCTBX snippets for Vim or NeoVim via neosnippets plugin.
- [cctbxsnips-Snipmate](https://github.com/MooersLab/cctbxsnips-snipmate) CCTBX snippets for Vim or NeoVim via snipmate plugin.
- [cctbxsnips-Atom](https://github.com/MooersLab/cctbxsnips-Atom) CCTBX snippets for Atom.


## Curve-fitting software
- [List of curve-fitting software](https://github.com/MooersLab/Curve-fitting-software) This list includes both proprietary and free software.


## Emacs related
Today's Emacs is not your grandfather's Emacs.
The median age of an Emacs user is 32, not 77, as you might expect for an editor that is about 40 years old.
This is due to a very active community of young users centered around several YouTube channels, Emacs Lisp being well-designed to customize Emacs, an online annual conference, the popularity of org-mode, and a welcoming community of developers.
Elisp was first used in Emacs 19 in 1985 with the GNU Emacs 19.3., about ten years after the start of the project.

It should be noted that Emacs is single-threaded.
This is a significant limitation. 
One group has started a project, called `lem`, that uses Common Lisp to build a text editor that is multithreaded and very much like Emacs. 
Unfortunately, Lem is not really user-ready in our experience. 
Perhaps, Emacs users will migrate to `lem` someday. 
In the meantime, it is worth continuing to use Emacs, knowing that a multithreading alternative is under development.

The Emacs project is open-source and run by several hundred volunteer core developers.
The project runs by consensus.
There is no succession issue.
The project's benevolent dictator for life stepped down about 15 years ago.
After doing so, an explosion of creativity occurred.

According to the [Lindy effect](https://www.sciencedirect.com/science/article/abs/pii/S0378437117305964?via%3Dihub), it is likely that Emacs will remain in use for another 50 years.
Exposure to elisp coding in Emacs leads some to pick up other languages in the Lisp family, including Clojure.
This, in turn, leads them to understand programming more deeply.

- [Popup menus of GNU Emacs core commands you want to master](https://github.com/MooersLab/emacs-learning-spiral-hydra)
- [Configuration for Emacs30 to support structured editing](https://github.com/MooersLab/emacs30venturatreesitterconfig)
- [Some simple hydras in Codeberg repo](https://codeberg.org/MooersLab/emacs-hydra-examples)
- [Compiling Emacs30 on Ventura (macOS 13.2) with tree-sitter](https://github.com/MooersLab/emacs30macos13treesitter) This protocol compiles Emacs from source with tree-sitter support for structured editing of computer code on macOS.
- [Compiling Emacs30 on Ubuntu22.04 LTS with tree-sitter](https://github.com/MooersLab/emacs30ubuntu22) This protocol compiles Emacs with tree-sitter support on Ubuntu.
- [crafted-emacs user config](https://github.com/MooersLab/crafted-emacs-config) My user configuration file (config.el) for the crafted-emacs profile. I did install use-package and used it to install several packages. The base profile has the Doom theme, Vertico completion stack, and eglot. I added my org-agenda config and my favorite key bindings. I am currently *luvin* it.
- [latex-emacs29 configuration](https://github.com/MooersLab/latex-emacs) A configuration file enhancing the use of LaTeX in Gnu Emacs version 29.0.5. Includes org-mode configuration.
- [latex-emacs28 configuration](https://github.com/MooersLab/latexemacs28) Similar to above but for Gnu Emacs version 28.
- [latex-emacs30 configuration](https://github.com/MooersLab/latexemacs30) Similar to above but for Gnu Emacs version 30.
- [scimax user.el](https://github.com/MooersLab/scimaxuserconfig) Scimax is the Emacs configuration that Dr. John Kitchin of Carniege-Mellon University is developing to support reproducible research by scientists with Gnu Emacs. The *user.el* file for scimax enables scimax users to add keybindings and packages. I added features from latex-emacs and config.org.
- [config.org](https://github.com/MooersLab/configorg) My default configuration file for GNU Emacs version 30.
- [Writing log template in Org-mode](https://github.com/MooersLab/writingLogTemplateInOrg) Template for tracking your actions, decisions, and plans for any serious writing project that takes more than one session to finish. The LaTeX version is listed in the LaTeX section for use on Overleaf or in Emacs.
- [Org-mode manuscript template](https://github.com/MooersLab/manuscriptInOrg) The manuscript will be exported to PDF after being run through LaTeX. This is for the first submission. This is for the lovers of org-mode. The export from org to PDF is fast and painless in Emacs.
- [Slides about workflow in LaTeX](https://github.com/MooersLab/BerlinEmacsAugust2022) These were presented to the Berlin Emacs Meetup August 2022. Regrettably, the talk was not recorded. It was a 90-minute presentation.
- [snippets for latex-mode in Emacs](https://github.com/MooersLab/snippet-latex-mode) LaTeX code snippets for yasnippets.
- [Quizzes about Emacs to improve recall of keybindings](https://github.com/MooersLab/qemacs) Ten minutes boosting your recall on a particular topic can save 10, 100, or 1000 hours of Google searches, especially if you are prone to getting side-tracked in the Google-verse.
- [Slides from talk about GhostText, Data Science Workshop, July 2022](https://github.com/MooersLab/DSW22ghosttext) GhostTexT rocks! It enables the editing of textboxes on web sites with Emacs. You can use GhostText to bring the full power of Emacs to Overleaf (*Important:*  use the legacy version rendering of the text area in Overleaf to get text imported into a LaTeX buffer).
- [Video link to talk about GhostText, Oklahoma Data Science Workshop, July 2022](https://mediasite.ouhsc.edu/Mediasite/Channel/python/watch/4da0872f028c4255ae12935655e911321d)
- [emacsconf 2021 talk about rendering molecular graphics with PyMOL in org literate programming files](https://emacsconf.org/2021/talks/molecular/) Video and comments.
- [emacsconf 2022 talk about using Emacs to edit Jupyter cells via GhostText and atomic-chrome](https://emacsconf.org/2022/talks/jupyter/) Video and comments.
- [emacsconf 2023 talk about using  to enhance productivity](https://emacsconf.org/2023/talks/voice/) Video, transcript, and comments.
- [EmacsATX Meetup Talk, 4 May 2022: functional programming in Emacs lisp](https://github.com/MooersLab/EmacsATX4May2022) Slides.

## Jupyter and Colab related

### Jupyter and PyMOL

PyMOL can be run in Jupyter via PyMOL's Python API.

#### Snippet libraries for direct use in Jupyter

Multiple extensions for Jupyter support the use of snippets.
However, the support does not include tab stops nor tab triggers, two standard features of snippet support in modern text editors.
The libraries with `plus` at the end of their name have a second copy of the code in a comment.
This copy is marked with the sites of the tab stops where you might want to change the parameter value from its default value.

##### Classics Notebook
PyMOL Python snippets for use in the Classic Jupyter Notebook with the `snippets_menu` notebook extension.

- [jupyternbclassicpymolpysnips](https://github.com/MooersLab/jupyternbclassicpymolpysnips)
- [jupyternbclassicpymolpysnipsplus](https://github.com/MooersLab/jupyterlabpymolpysnipsplus)

##### JupyterLab

PyMOL Python snippets for use in JupyterLab with the jupyterlab-snippets extension.

- [jupyterlabpymolpysnips](https://github.com/MooersLab/jupyterlabpymolpysnips) PyMOL Python snippets for use in JupyterLab with the jupyterlab-snippets extension.
- [jupyternbclassicpymolpysnipsplus](https://github.com/MooersLab/jupyternbclassicpymolpysnipsplus)

PyMOL Python snippets for use with the elyra-snippets extension and with PyMOL.
These snippets can be retrieved with tags in the elyra-snippet GUI.

- [taggedpymolpysnips](https://github.com/MooersLab/taggedpymolpysnips)
- [taggedpymolpysnipspymolpysnipsplus](https://github.com/MooersLab/taggedpymolpysnipspymolpysnipsplus)

#### Snippet libraries for using external editors of Jupyter notebooks
These editors work in Jupyter Notebooks via the GhostText browser plugin.

- [jupyter-vsc-pymolpysnips](https://github.com/MooersLab/jupyter-vsc-pymolpysnips)
- [jupyter-st3-pymolpysnips](https://github.com/MooersLab/jupyter-st3-pymolpysnips)
- [jupyter-emacs-pymolpysnips](https://github.com/MooersLab/jupyter-emacs-pymolpysnips)
- [jupyter-ultisnips-pymolpysnips](https://github.com/MooersLab/jupyter-ultisnips-pymolpysnips)
- [jupyter-snipmate-pymolpysnips](https://github.com/MooersLab/jupyter-snipmate-pymolpysnips)
- [jupyter-neosnippets-pymolpysnips](https://github.com/MooersLab/jupyter-neosnippets-pymolpysnips)
- [jupyter-atom-pymolpysnips](https://github.com/MooersLab/jupyter-atom-pymolpysnips)

##### Demo of GhostText with Jupyter and Emacs

- [emacsconf 2022 talk about using Emacs to edit Jupyter cells via GhostText and atomic-chrome](https://emacsconf.org/2022/talks/jupyter/)

### Colab and PyMOL
- [colabOpenSourcePyMOLpySnips](https://github.com/MooersLab/colabOpenSourcePyMOLpySnips) PyMOL Python snippets for use in Colab with open source PyMOL.
- [colabPyMOLpySnips](https://github.com/MooersLab/colabPyMOLpySnips) PyMOL Python snippets for use in Colab with the incentive PyMOL.

### CCTBX specific
- [Jupyterlab cctbx snippets](https://github.com/MooersLab/jupyterlabcctbxsnips) CCTBX snippets for JupyterLab with the jupyterlab-snippets extension or the jupyterlab-snippets-mutlimenus extension.
- [Jupyterlab cctbx plus snippets](https://github.com/MooersLab/jupyterlabcctbxsnipsplus) The variant of the jupyterlabcctbxsnips library with comments to guide editing of the snippets.
- [Colab cctbx snippets](https://github.com/MooersLab/colabcctbxsnips) Colab snippets.


## Experimental designs

### Experimental designs for crystal growth
We provide easy and fast-to-deploy experimental designs for crystallization setups in Excel workbooks.
These designs take three minutes to customize for your experimental needs.
Plots of the results against factor level for each factor are automatically generated, thereby saving the users many hours of tedious coding of the plots of the data for each crystallization tray.
These workbooks could be adapted to other kinds of experiments.

The OFAT experiments are often used to screen for active factors.
The active factors can then be used in DSD designs to find the optimal conditions to return large crystals.
OFAT experiments are inappropriate for this objective because they do not measure interactions between factors.
Factor interactions are quite common in the crystallization of proteins.

The DSDs tend to be limited to three active factors because of their small size and weaker statistical power.
Larger traditional response surface method designs (RSM) should be used if more factors are suspected of being active or if two or more interactions are expected.
DSD can be thought of as a subset of RSMs.
Their small size is attractive for protein crystallization where the sample is expensive and scarce.
The small size of DSD experiments opens up the possibility of replicating these experiments to get a measure of the variance.


- [Vary One-Factor-at-a-Time (OFAT) experimental designs](https://github.com/MooersLab/ofat4xtals)
- [Definitive Screening Designs](https://github.com/MooersLab/dsd4xtals)

## LaTeX related
Until recently, I wrote a lot in Emacs on 750words.com via GhostText.
I configured the atomic-chrome package for Emacs to go into LaTeX mode when GhostText connects to 750words.
I can also use Emacs to write and edit text in Overleaf via atomic-chrome and GhostText.
This is a very cool way to extend Emacs to websites that have weaker support for editing text.

Now I use voice-to-text to dictate in 750words.com or Overleaf.
I use voice commands to insert snippets containing LaTeX code.
See the [](https://github.com/MooersLab/MooersLab/blob/main/README.md#voice-computing-for-enchanced-productivity) section below.


- [LaTeX bare bones template file](https://github.com/MooersLab/barebonesLaTeX/tree/main) This template is for those people want make a simple document without a lot of bells-and-whitsles.
- [LaTeX tips](https://github.com/MooersLab/latextips)
- [Configuration for Emacs30 to support structured editing](https://github.com/MooersLab/emacs30venturatreesitterconfig)
- [latex-emacs29 configuration](https://github.com/MooersLab/latex-emacs) A configuration file enhancing the use of LaTeX in Gnu Emacs version 29. This is the current release version of Gnu Emacs. Includes org-mode configuration.
- [latex-emacs28 configuration](https://github.com/MooersLab/latexemacs28) Similar to above but for Gnu Emacs version 28.
- [latex-emacs30 configuration](https://github.com/MooersLab/latexemacs30) Similar to above but for Gnu Emacs version 30.
- [Slides about workflow in LaTeX](https://github.com/MooersLab/BerlinEmacsAugust2022) presented to the Berlin Emacs Meetup August 2022. Not recorded. It was a 90-minute lecture.
- [slideshowTemplateInLaTeX](https://github.com/MooersLab/slideshowTemplateLaTeX) Slideshow template with use with the LaTeX package Beamer that supports the making of slides. Our templates makes slides that do not look like they were made in LaTeX because we hide the navigation icons that no one ever uses and replace the triangles in bulleted lists with round bullets. Our slides look like they were made in PowerPoint.
- [posterInLaTeX](https://github.com/MooersLab/posterInLaTeX) Uses beamer to make a poster via a simple design. Enables whipping together a poster in a few hours. It is much easier than using a gaint slide in PowerPoint. Our approach is also saner than the default approach to making a poster with Beamer.
- [LaTeX manuscript template](https://github.com/MooersLab/manuscriptInLaTeX) Generic template for the first submission as a PDF.
- [Writing log template in LaTeX](https://github.com/MooersLab/writingLogTemplate) Place to track progress and plans behind a manuscript.
- [Annotated bibliography template in LaTeX](https://github.com/MooersLab/annotatedBibliography) Every writing project needs one of these. These are grossly underutilized. They are good for recalling the relevant features of a paper.
- [Diary for 2024 in LaTeX](https://github.com/MooersLab/diary2024inLaTeX) Designed for use on Overleaf.com but can compile locally. Each day is a section. Each month is a chapter. Has an automatically generated index (most markdowns cannot generate indices). Very feature-rich and ready to use. Makes a great electronic scientific notebook because it is searchable and indexed. >1000 page document at end of years compiles to PDF in under a minute on overleaf.
- [snippets for latex-mode in Emacs](https://github.com/MooersLab/snippet-latex-mode) My LaTeX code snippets for yasnippets.
- [The writer's creed](https://github.com/MooersLab/thewriterslaw) Guidelines for greater productivity as a writer.
- [bib2item3](https://github.com/MooersLab/bib2item3) Python script to convert bibtex.bib file to bibitems in tex file format. Bibitems are required by some publishers. They are a pain to create manually.
- [LaTeX Voice In Plus library](https://github.com/MooersLab/latex-voice-in) Speech-to-text commands for inserting LaTeX markup.

## Molecular Graphics related
[Collection of links for a 15-hour course on Molecular Graphics](https://mooerslab.github.io/MolecularGraphicsLinks/index.html)


#### PyMOL
- [pymolrc](https://github.com/MooersLab/pymolrc) My pymolrc file.
- [pymolsnips](https://github.com/MooersLab/pymolsnips) A large collection of PyMOL macro language (pml) code snippets. Contains link to a webpage with extensive instructions on installing 19 text editors.
- [pymolshortcuts](https://github.com/MooersLab/pymolshortcuts) A large collection of functions mapped to aliases or shortcuts. This colleciton of functions is very useful for non-coders.
- [EasyPyMOL](https://github.com/MooersLab/EasyPyMOL) Support for horizontal scripting in PyMOL.
- [orgpymolpysnips](https://github.com/MooersLab/orgpymolpysnips) Support for generating computational narratives (literate programming plus interactive computing) in org-mode with PyMOL.
- [rstudiopymolpysnips](https://github.com/MooersLab/rstudiopymolpysnips) Support for literate programming in Rstuido with PyMOL.
- [taggedpymolpysnips](https://github.com/MooersLab/taggedpymolpysnips) Support for literate programming in JuptyerLab with tagged snippets with the elyra-snippets extension and with PyMOL.
- [jupyterlabpymolpysnips](https://github.com/MooersLab/jupyterlabpymolpysnips) PyMOL Python snippets for use in JupyterLab with the jupyterlab-snippets extension.
- [jupyternbclassicpymolpysnips]() PyMOL Python snippets for use in the Classic Jupyter Notebook (invoked with `jupyter nbclassic` with Jupyter Notebook version 7).
- [colabOpenSourcePyMOLpySnips](https://github.com/MooersLab/colabOpenSourcePyMOLpySnips) PyMOL Python snippets for use in Colab with open source PyMOL.
- [colabPyMOLpySnips](https://github.com/MooersLab/colabPyMOLpySnips) PyMOL Python snippets for use in Colab with the incentive version of PyMOL.
- [PyMOL wall hangings](https://github.com/MooersLab/PyMOLwallhangings) Protocol for making oversized images to be framed and hung on a wall.
<!--
## Structure-based Drug Design
-->

## R statistical program
- [rstudiopymolpysnips](https://github.com/MooersLab/rstudiopymolpysnips) Support for literate programming in Rstuido with python code for PyMOL.


## Small Angle Scattering
- [SmallAngleScatteringWebpage](https://mooerslab.github.io/SmallAngleScatteringWebpage/index.html)

## Time management
- [TimeSpent](https://github.com/MooersLab/timeSpent) Time tracking by project with Google Sheets.

## Supercomputing related
Includes high performance computing (HPC), cluster computing, and cloud computing.

- [Bash functions for Schooner at OSCER](https://github.com/MooersLab/bashFunctions4oscer)
- [Emacs configuration file for schooner supercomputer](https://github.com/MooersLab/emacs4oscer)
- [Multiple file transfer with scp](https://github.com/MooersLab/multipleFileTransfer)
- [Vim configuration file for the schooner supercomputer at OU-Norman](https://github.com/MooersLab/vimrc4oscer)
- [Vim configuration file for SSRL SMB cluster](https://github.com/MooersLab/vimrc4ssrl)
- [Tutorial for biologists on using the supercomputer at OU-Norman](https://github.com/MooersLab/oscer-supercomputer-tutorial)

## Vim (and Neovim)
- [Vim configuration file](https://github.com/MooersLab/vimrc) Current vimrc file for Mac OSX 10.15
- [Vim configuration file for schooner supercomputer](https://github.com/MooersLab/vimrc4oscer)
- [Vim configuration file for SSRL SMB cluster](https://github.com/MooersLab/vimrc4ssrl)
- [Neovim configuration file](https://github.com/MooersLab/neovim-init-file)
- [qvim](https://github.com/MooersLab/qvim) Quiz about Vim commands to improve your recall of the commands after a break from using Vim.

## Voice Computing

Voice computing can be divided into three activities:

- speech-to-text (dictation)
- speech-to-commands
- speech-to-code

The speech-to-text is the easiest to master, the most widely applicable, and the most effective at enhancing the productivity for academics.

### Index of subsections

- [Software that I use](https://github.com/MooersLab#review-of-software-of-the-voice-copmputing-software-that-I-have-used)
- [Talon Voice for voice control and computing](https://github.com/MooersLab#talon-voice-related)
- [Voice In Plus for dictation and voice control in the web](https://github.com/MooersLab#voice-in-plus-related)
- [Whisper for dictation, includes my text replacements](https://github.com/MooersLab#whisper-related)
- [Voice Typing in Google Docs for dictation](https://github.com/MooersLab#voice-typing-in-google-docs-related)
- [Words counts before and after adopting ](https://github.com/MooersLab#Word-Counts-before-and-after-adopting-Voice-Computing)
- [Voice computing related talks](https://github.com/MooersLab#voice-computing-related-talks)


### Review of the  software that I have used

My sampling of the available -related software is highly skewed towards the Mac operating system and Google Chrome.
I have yet to complete a comprehensive survey of the software available for Windows, Linux, and other browsers.
If you are a user of such systems then the review below will give you a taste of what may be available for these other operating systems

**Voice Typing** is widely available through Google Docs.
It is more accurate than the Voice Control that comes with the Mac and MS Word.
**Voice Typing** supports almost 100 voice commands but does not support custom commands.

**Voice In Plus** has similar accuracy to **Voice Typing** with the addition of custom commands.
I use the latter every day for dictation for first drafts.
I do the rewriting using the keyboard.

OpenAI's **Whisper** may be an order of magnitude more accurate.
It has a latency issue, so live transcription and interactive editing is difficult.
It is also not easy to fine-tune with custom commands.

My primary use of **Whisper** is for transcribing audio files.
I provide Python scripts to correct the initial transcript.
These corrections include expanding contractions.
This code also supports inserting simple commands like `new paragraph` during dictation because **whisper** does not know how to break up a transcript into paragraphs.

A very new use of **Whisper** for me is inside Emacs.
I had been aware of its availability for four months.
After my third attempt, I finally figured out how to run **Whisper** in Emacs via the [**whisper.el** package](https://github.com/natrys/whisper.el?tab=readme-ov-file).
The package automates compiling the *whisper.cpp* software and downloading the Whisper LLM.
You record a local audio file of your dictation, and then you transcribe that audio file into text that appears in the current buffer in Emacs.
The `M-H r` keybinding starts the audio recording, and the `C-u M-x r` keybinding transcribes the audio file.
Here, `H` is for the Hyper key; I have it mapped to the righthand command key (alt-key) on a non-Mac keyboard.

The natural unit of dictation with `whisper.el` seems to be the paragraph.
This form of dictation is less interactive than Voice In Plus where you can use the keyboard to make edits to currently dictated sentence.
I have yet to figure out the elisp code to apply my text replacements in the transcription step.

The **Superwhisper.** **app** for the Mac is interesting.
It supports dictation in e-mail and elsewhere.
Its support for custom commands is limited; it still needs to support bulk uploading of text replacements before it will interest me.
You have to pay a subscription fee to access all its features.
Its features may appeal to people with numerous electronic devices that need to be synced with their main computer.

**Talon Voice** supports all three activities, but speech-to-text accuracy needs to catch up to Voice Typing and Voice In Plus in my experience.
I am currently using Talon Voice for the last two activities.
I plan to increase my use of Talon Voice for dictation.

The **Talon Voice** software is designed to be used by non-coders.
It can be configured with Talonscript files that have a simple syntax that is a subset of Python.
You can customize Talon Voice extensively using the Talonscript files without writing any Python code.

Voice computing supports extending your productivity when you get tired of typing.
Voice computing also supports issuing commands and dictating text while standing.
Voice computing could be a cure for the envy of those colleagues who have standing desks.
You can speak commands to your computer while standing 20 feet away from it and looking out the window.
You can give your body and eyes a break from sitting and staring at the computer screen while remaining productive.

### Word Counts before and after adopting Voice Computing

I have seen a three-fold increase in the total number of words captured in September and October 2023 compared to June and July 2023 before I took up speech-to-text in mid-August 2023.
I have had the same amount of out-of-town travel during the first two periods.
I did not make a conscious effort to capture more words per day.

<p align="center"><img src="./images/words6.png" alt="HTML5 Icon" style="width:612px;height:312px;"></p>

On the day after Thanksgiving in 2023, I generated almost 12,000 words.
I made a concerted effort to generate at least 5,000 words a day from that point to just before Christmas.
Then family obligations reduced my daily word generation.
Nonetheless, I had a five-fold increase in the total word count for November and December.
A six-sevenfold increase may be possible.
A five-fold increase in word count may be more sustainable if you consciously try.
A three-fold increase is more realistic with all of the disruptions from doing experiments, administration, teaching, service, and work-related travel.

The slight decrease in word count after the new year may reflect a shift in my focus toward turning more of my writing into publishable products.
This decrease may reflect more effort focused on editing text.

I was surprised that there was not a more significant decrease.
I may have compensated by using a digital voice recorder (DVR) in mid-January 2024 during my 25-minute commutes to my office.
Much of my mutterings are rubbish, but I occasionally harvest useful thoughts.
The DVR has extended my generative writing time by 30-60 minutes daily.


Spending more time on rewriting will lead to fewer new words generated if the time spent on writing is constant.
Rewriting is very time-consuming; it can take as much or more time as generating the text initially.
Text written for grant applications and articles will take even more time because it needs to be highly polished.
Sufficient time has to be scheduled for it.
I plan to spend more time rewriting, so you can expect the new words generated in the next bimonthly report to be further reduced.


### What about Mac's Dictation and Voice Control software?
One alternative is to use the built-in Dictation software for Mac.
Four months ago, the Mac dictation software was worse than the alternatives, like Voice In.
I tried it again on March 22, 2024,
The error rate is now reduced enough to give it another try.

Its advantage is that it can operate anywhere.
It works inside Emacs and on webpages, including webmail applications like Outlook and Gmail.
Its disadvantage is that it cannot be customized with text replacement libraries.

For older Intel chip-based Macs, the Dictation software relies on an available internet connection.
The generated sound waves are sent to a server run by Apple and then returned as text.
I found that the delay that is caused by this transfer to unnoticeable.
However, I do not have a M-chip-based Mac to test.

Sadly, the Voice Control software provided by the Mac OS has not improved its performance since I last tried it.
Its error rate is too high to use for dictation.
The advantage of this software is that it supports customized commands.

### Whisper and a Digitial Voice Recorder
I have used the dictated text transcribed by Whisper to a much lesser extent during my morning commutes.
There is often a lot of garbage text that Whisper inserts during long pauses.
It generally takes a lot of effort to parse the transcribed text.
It is easier to redo the dictation via Voice In and make corrections as you go.
The exercise of carrying out the dictation initially during the commute is analogous to generating a verbal rough draft in my mind.
Once the initial draft has been composed, it is easier to redo it with better word choices.

On several occasions, my digital voice recorder turned off accidentally when placed in my shirt pocket at the start of my commute.
To my dismay, upon arriving at my office, I discovered that I needed to repeat what I had dictated.
Nonetheless, I could recapitulate much of what I had dictated just a half hour earlier.
The text transcribed by Whisper is more valuable as a backup to trigger my memory rather than as a rough draft.
I have not yet tried to feed the transcribed text from Whisper to ChatGPT with the instructions to parse it.



Below are links to programming tools to aid the adoption of voice computing.

### Talon Voice-related
- [Expand dictated contractions automatically](https://github.com/MooersLab/talon-contractions)
- [Open favorite web pages by voice commands](https://github.com/MooersLab/talon-webpages)
- [Master Talon Voice phonetic alphabet with interactive quiz written in Python](https://github.com/MooersLab/talon-voice-quizzes)
- [Master Talon Voice with interactive quiz written in elisp for Emacs](https://github.com/MooersLab/talon-voice-quiz.el)


### Voice In Plus related

This browser plugin works in Google Chrome and Microsoft's Edge.
It depends on the browser's Speech-to-Text API.
Interactive sessions with it persist for up to 5 to 10 paragraphs, depending on your activity and speed of dictation.
If you dictate too quickly, you will get ahead of the software and it will hang. 
You might lose text for some of the words you dictated.
Nonetheless, this software is superior to Mac dictation software, which will only persist for an average of three sentences because it sends the sound waves to a language model located on a remote server.



#### Generic
- [Master basic Voice In commands with interactive Python quiz](https://github.com/MooersLab/voice-in-basics-quiz)
- [Master basic Voice In commands with an interactive quiz in Emacs](https://github.com/MooersLab/voice-in-basics-quiz.el)
- [Library of 94 English contractions](https://github.com/MooersLab/voice-in-plus-contractions)
- [Full library of commands for Voice In Plus](https://github.com/MooersLab/voice-in-plus-commands)
- [Org-mode](https://github.com/MooersLab/org-mode-voice-in/tree/main)
- [OUHS-related acronym expansions](https://github.com/MooersLab/ouhs-voice-in)
- [LaTeX](https://github.com/MooersLab/latex-voice-in)
- [Generate new writing project commands](https://github.com/MooersLab/new-writing-project-voice-in)

#### Structural biology method
- [Biological crystallography (MX)](https://github.com/MooersLab/biological-crystallography-voice-in)
- [Cryogenic electron microscopy (CryoEM and CryoET)](https://github.com/MooersLab/cryoem-voice-in)
- [Small Angle Scattering (SAS)](https://github.com/MooersLab/sas-voice-in)

#### Data analysis
- [Design of Experiments (DoE)](https://github.com/MooersLab/design-of-experiments-voice-in)
- [Bayesian Data Analysis (BDA)](https://github.com/MooersLab/bayesian-data-analysis-voice-in/blob/main/README.md)
- [Artificial intelligence (AI)](https://github.com/MooersLab/artificial-intelligence-voice-in)
- [Software Developement](https://github.com/MooersLab/software-development-voice-in)
  

#### Funding Agency related
- [NIH grants](https://github.com/MooersLab/nih-grants-voice-in)


### Voice Typing in Google Docs related
- [Master Voice Typing commands with interactive quiz](https://github.com/MooersLab/voice-typing-quiz)


### Whisper related
- [Bash function to transcribe audio files with whisper](https://github.com/MooersLab/bash-whisper-transcription)


### Voice computing-related talks
I have given two talks on this topic: one at the regional level and one at the international level.

- [Data Science Workshop talk on speech-to-text, 2023 Nov. 16](https://mediasite.ouhsc.edu/Mediasite/Channel/python/watch/21e8b9a65d044d01a264df1f19db261b1d)
- [emacsconf23 talk speech-to-text and speech-to-commands, 2023 Dec. 2 on YouTube](https://www.youtube.com/watch?v=Z7l1ImjXOWM)
- [ditto but on the emacsonf.org website](https://emacsconf.org/2023/talks/voice/)


## Writing productivity tools
These are some programming tools designed to support greater writing productivity.
There are three elements: progress tracking, support for manuscript writing in LaTeX, and the writing log.
The last might be the most essential tool for organizing and managing a writing project.
It is analogous to a project-specific laboratory notebook.

### Progress tracking
For writing tasks that cannot be completed in one sitting, progress tracking can support momentum and enthusiasm for the project.

- [Track writing progress in 2024 and 2025](https://github.com/MooersLab/writing-progress-2024-25)
- [The writer's creed](https://github.com/MooersLab/thewriterslaw) Guidelines for greater productivity.
- [Writing contract template](https://github.com/MooersLab/writingContract) This contract is in Microsoft Word, Markdown, LaTeX, and org-mode. This accountability system works only if your partner is similarly committed to daily writing. I had a good run of four years with one person from out of state. I would consider doing this again.
- [TimeSpent](https://github.com/MooersLab/timeSpent) Hourly time tracking by project with Google Sheets. This is useful for making monthly time reports and learning how much various writing projects actually take.

### Manuscript writing support

- [LaTeX manuscript template](https://github.com/MooersLab/manuscriptInLaTeX) Generic template for the first submission as a PDF.
- [Annotated bibliography Template in LaTeX](https://github.com/MooersLab/annotatedBibliography) Every writing project needs one of these.
- [bib2item3](https://github.com/MooersLab/bib2item3) Python script to convert bibtex.bib file to bibitems in tex file format. Bibitems are required by some publishers. They are a pain to create manually.
- [Emacsconf 2022 talk about GhostText on YouTube, December 2022](https://www.youtube.com/watch?v=2NPUDYAOgW0&t=3s) Includes a demonstration of using Emacs to edit a document stored in Overleaf.
- [LaTeX Voice In Plus library of speech-to-text commands](https://github.com/MooersLab/latex-voice-in)

### Writing log for planning manuscripts

- [Writing Log template in LaTeX](https://github.com/MooersLab/writingLogTemplate). This is the favored format. LaTeX beginning users can easily use this document on Overleaf without any configuration.
- [Writing log template in Org-mode](https://github.com/MooersLab/writingLogTemplateInOrg) Has all of the features of the LaTeX variant. Favored by many Emacs users. Org-mode is a powerful analog of markdown that can interpret LaTeX code blocks.
- Org-mode is vastly more capable than markdown. The most remarkable feature is the tables that act like spreadsheets. If you are already comfortable with LaTeX, org-mode will be a step backward for writing documents.
Nonetheless, it is still useful for literate programming (or interactive computational narratives), but the interactive display of large images has to be done in separate buffers. Org-roam is useful for knowledge base management, although Obsidian provides a cleaner experience.
I still have trouble with org-agenda.
Few people have mastered it.

- [Writing log template in reStructuredText](https://github.com/MooersLab/writing-log-rst) reStructuredText is used by programmers for documentation.
- [Writing log template in Markdown](https://github.com/MooersLab/writing-log-md) Markdown variant. Rendered to PDF by most good text editors.
- [Writing log template in ODT](https://github.com/MooersLab/writing-log-odt) ODT can be read by Open Office, LibreOffice, and MS Word.
- [Writing log template in DOCX for MS Word](https://github.com/MooersLab/writing-log-docx) MS Word variant--the least suitable format for this task, in my opinion.

## Videos related to these repositories
- [Snippets in Jupyter Notebooks](https://www.youtube.com/watch?v=LjJvhfJvla4), OKC Python Meetup, 10 May 2019.
- [Why develop a snippet library for Jupyter in your subject domain?](https://www.youtube.com/watch?v=sZNCAwW5dYg&amp;t=11s)  JupyterConn 2020.
- [Reproducible molecular graphics with Org-mode](https://www.youtube.com/watch?v=ZTocGPS-Uqk&amp;t=2s), EmacsConf 2021.
- [Edit live Jupyter notebook cells with Emacs](https://www.youtube.com/watch?v=2NPUDYAOgW0), EmacsConf 2022.
- [Enhancing productivity with voice computing](https://emacsconf.org/2023/talks/voice/), EmacsConf 2023.
- [Managing multiple writing projects](https://mediasite.ouhsc.edu/Mediasite/Channel/python/watch/bc2777b248ff4fa4959b9bfed9b0e84a1d), Data Science Workshop, Jan. 2024.


## Update History

|Version      | Changes                                         | Date            |
|:-----------:|:-----------------------------------------------:|:---------------:|
| Version 0.5|  Fixed typos in README.md                       | 2024 April 11    |


## Sources of funding

- NIH: R01 CA242845
- NIH: R01 AI088011
- NIH: P30 CA225520 (PI: R. Mannel)
- NIH P20GM103640 and P30GM145423 (PI: A. West)

**MooersLab/MooersLab** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on his GitHub profile 👋.

<!--

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
- 👋
-->
