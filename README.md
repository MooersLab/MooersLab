# MooersLab

This site contains the public repositories of the Dr. Blaine Mooers Lab, Department of Biochemistry and Molecular Biology, College of Medicine, University of Oklahoma Health Sciences Center, Oklahoma City, Oklahoma, USA.
My lab determines the structures of biomolecular molecules and their complexes with drugs using mostly [X-ray crystallography](https://en.wikipedia.org/wiki/X-ray_crystallography#Biological_macromolecular_crystallography) and sometimes [small angle X-ray scattering](https://en.wikipedia.org/wiki/Small-angle_X-ray_scattering), a method that does not require crystals. 
We grow crytals using advanced experimental design methods and collect X-ray diffraction data inhouse and frequently at the [Stanford Synchrotron Radiation LightSource](https://www-ssrl.slac.stanford.edu/content/) and sometimes at the four other major light sources in the US.
We also do structure-based drug design using supercomputers.

We are not computer scientists, but we do write some code from time-to-time.
We made some software tools to ease the writing of PyMOL scrpts for making molecular images.
These tools are available for the top 19 text editors and for the Jupyter, Colab, and Rmarkdown notebooks. 
All of these text editors can make your work lighter and have many wonderful features, but Emacs is our favorite because it is by far the most customizable thanks to Emacs Lisp.

The repositories are grouped by category.
Some repositories are listed in several categories.
This listing is still a work in progress. 
Many repositories have yet to be added.
Seventeen repos are forks to other people's repositories.
Go to the [repositories tab](https://github.com/MooersLab?tab=repositories) to see the full list of repositories.

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
- [JointProb](https://github.com/MooersLab/jointprob1D) Rmarkdown and jupyer notebooks for the Saturday JointProb study group.

## Blog
- [Lab website with blog posts](https://mooerslab.github.io/year-archive/)


## Crystallographic computing

### CCTBX related

<a id="cctbxsnips-for-notebooks"><h4>For use in notebooks</h4></a>

- [Jupyterlab cctbx snippets](https://github.com/MooersLab/jupyterlabcctbxsnips) CCTBX snippets for JupyterLab with the jupyterlab-snippets extension or the jupyterlab-snippets-mutlimenus extension.
- [Jupyterlab cctbx plus snippets](https://github.com/MooersLab/jupyterlabcctbxsnipsplus) The variant of the jupyterlabcctbxsnips library with comments to guide editing of the snippets.
- [Colab cctbx snippets](https://github.com/MooersLab/colabcctbxsnips) Colab snippets.

<a id="cctbxsnips-for-editors"><h4>For use in text editors</h4></a>

- [cctbxsnips-Emacs](https://github.com/MooersLab/cctbxsnips-Emacs) CCTBX snippets for the yasnippet snippet system in for Emacs.
- [cctbxsnips-SublimeText3](https://github.com/MooersLab/cctbxsnips-SublimeText3) CCTBX snippets for Sublime Text 3 (ST3).
- [cctbxsnips-VSC](https://github.com/MooersLab/cctbxsnips-VSC) CCTBX snippets for Visual Studio Code (VSC).
- [cctbxsnips-UltiSnips](https://github.com/MooersLab/cctbxsnips-Ultisnips) CCTBX snippets for Vim or NeoVim via UltiSnips plugin.
- [cctbxsnips-neosnippets](https://github.com/MooersLab/cctbxsnips-neosnippets) CCTBX snippets for Vim or NeoVim via neosnippets plugin.
- [cctbxsnips-Snipmate](https://github.com/MooersLab/cctbxsnips-snipmate) CCTBX snippets for Vim or NeoVim via snipmate plugin.
- [cctbxsnips-Atom](https://github.com/MooersLab/cctbxsnips-Atom) CCTBX snippets for Atom.


## Curvefiting software
- [List of curve-fitting software](https://github.com/MooersLab/Curve-fitting-software) This list includes both proprietary and free software.


## Emacs related
- [crafted-emacs user config](https://github.com/MooersLab/crafted-emacs-config) My user configuration file (config.el) for the crafted-emacs profile. I did install use-package and used it to install several packages. The base profile has the Doom theme, Vertico completion stack, and eglot. I added my org-agenda config and my favorite key bindings. I am currently *luvin* it. 
- [latex-emacs29 configuration](https://github.com/MooersLab/latex-emacs) A configuration file enhancing the use of LaTeX in Gnu Emacs version 29.0.5. Includes org-mode configuration.
- [latex-emacs28 configuration](https://github.com/MooersLab/latexemacs28/blob/main/README.md) Similar to above but for Gnu Emacs version 28.
- [latex-emacs30 configuration](https://github.com/MooersLab/latexemacs28/blob/main/README.md) Similar to above but for Gnu Emacs version 30.
- [scimax user.el](https://github.com/MooersLab/scimaxuserconfig) Scimax is the Emacs configuration that John Kitchin is developing to support reproducible research by scientists with Gnu Emacs. The *user.el* file for scimax enables scimax users to add keybindings and packages. I added features from latex-emacs and config.org.
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

## Jupyter and Colab related

### PyMOL specific
- [taggedpymolpysnips](https://github.com/MooersLab/taggedpymolpysnips) Support for literate programming in JuptyerLab
Lab with tagged snippets with the elyra-snippets extension and with PyMOL.
- [jupyterlabpymolpysnips](https://github.com/MooersLab/jupyterlabpymolpysnips) PyMOL Python snippets for use in JupyterLab with the jupyterlab-snippets extension.
- [colabOpenSourcePyMOLpySnips](https://github.com/MooersLab/colabOpenSourcePyMOLpySnips) PyMOL Python snippets for use in Colab with open source PyMOL.
- [colabPyMOLpySnips](https://github.com/MooersLab/colabPyMOLpySnips) PyMOL Python snippets for use in Colab with the incentive PyMOL.
- [emacsconf 2022 talk about using Emacs to edit Jupyter cells via GhostText and atomic-chrome](https://emacsconf.org/2022/talks/jupyter/)

### CCTBX specific
- [Jupyterlab cctbx snippets](https://github.com/MooersLab/jupyterlabcctbxsnips) CCTBX snippets for JupyterLab with the jupyterlab-snippets extension or the jupyterlab-snippets-mutlimenus extension.
- [Jupyterlab cctbx plus snippets](https://github.com/MooersLab/jupyterlabcctbxsnipsplus) The variant of the jupyterlabcctbxsnips library with comments to guide editing of the snippets.
- [Colab cctbx snippets](https://github.com/MooersLab/colabcctbxsnips) Colab snippets.


## LaTeX related
Note that I currently write alot in Emacs on 750words.com via GhostText. 
I configured the atomic-chrome package for Emacs to go into LaTeX mode when GhostText connects to 750words. 
I can also use Emacs to write and edit text in Overleaf via atomic-chrome and GhostText.
This is a very cool way of extending Emacs to websites that have weaker support for editing text.

- [latex-emacs29 configuration](https://github.com/MooersLab/latex-emacs) A configuration file enhancing the use of LaTeX in Gnu Emacs version 29.0.5. This is the current release version of Gnu Emacs. Includes org-mode configuration.
- [latex-emacs28 configuration](https://github.com/MooersLab/latexemacs28/blob/main/README.md) Similar to above but for Gnu Emacs version 28.
- [latex-emacs30 configuration](https://github.com/MooersLab/latexemacs28/blob/main/README.md) Similar to above but for Gnu Emacs version 30.
- [Slides about workflow in LaTeX](https://github.com/MooersLab/BerlinEmacsAugust2022) presented to the Berlin Emacs Meetup August 2022. Not recorded. It was 90-minute lecture.
- [slideshowTemplateInLaTeX](https://github.com/MooersLab/slideshowTemplateLaTeX) Slideshow template in Beamer makes slides that do not look like they were made in LaTeX.
- [posterInLaTeX](https://github.com/MooersLab/posterInLaTeX) Uses beamer to make a poster via a simple design. Enables whipping together a poster a few hours. It is much easier than using powerpoint.
- [LaTeX manuscript template](https://github.com/MooersLab/manuscriptInLaTeX/edit/main/README.md) Generic template for the first submission as a PDF.
- [Writing log template in LaTeX](https://github.com/MooersLab/writingLogTemplate) Place to track progress and plans behind a manuscript.
- [Annotated bibliography Template in LaTeX](https://github.com/MooersLab/annotatedBibliography) Every writing project needs one of these.
- [Diary for 2023 in LaTeX](https://github.com/MooersLab/diary2023inLaTeX) Each day is a section. Each month is a chapter. Has an automatically generated index (most markdowns cannot generate indices). Very feature-rich and ready to use.
- [snippets for latex-mode in Emacs](https://github.com/MooersLab/snippet-latex-mode) My LaTeX code snippets for yasnippets.
- [The writer's creed](https://github.com/MooersLab/thewriterslaw) Guidelines for greater productivity as a writer.


## Molecular Graphics related
[Collection of links for a 15-hour course on Molecular Graphics](https://mooerslab.github.io/MolecularGraphicsLinks/index.html)


#### PyMOL
- [pymolrc](https://github.com/MooersLab/pymolrc) My pymolrc file.
- [pymolsnips](https://github.com/MooersLab/pymolsnips) A large collection of PyMOL macro language (pml) code snippets. Contains link to a webpage with extensive instructions on installing 19 text editors.
- [pymolshortcuts](https://github.com/MooersLab/pymolshortcuts) A large collection of functions mapped to aliases or shortcuts. This colleciton of functions is very useful for non-coders.
- [EasyPyMOL](https://github.com/MooersLab/EasyPyMOL) Support for horizontal scripting in PyMOL.
- [orgpymolpysnips](https://github.com/MooersLab/orgpymolpysnips) Support for literate programming in org-mode with PyMOL.
- [rstudiopymolpysnips](https://github.com/MooersLab/rstudiopymolpysnips) Support for literate programming in Rstuido with PyMOL.
- [taggedpymolpysnips](https://github.com/MooersLab/taggedpymolpysnips) Support for literate programming in JuptyerLab
Lab with tagged snippets with the elyra-snippets extension and with PyMOL.
- [jupyterlabpymolpysnips](https://github.com/MooersLab/jupyterlabpymolpysnips) PyMOL Python snippets for use in JupyterLab with the jupyterlab-snippets extension.
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

## Supercomputing related (includes high performance computing (HPC), cluster computing, cloud computing)
- [Bash functions for Schooner at OSCER](https://github.com/MooersLab/bashFunctions4oscer)
- [Emacs configuration file for schooner supercomputer](https://github.com/MooersLab/emacs4oscer)
- [Multiple file transfer with sshpass and scp](https://github.com/MooersLab/multipleFileTransfer)
- [Vim configuration file for the schooner supercomputer at OU-Norman](https://github.com/MooersLab/vimrc4oscer) 
- [Vim configuration file for SSRL SMB cluster](https://github.com/MooersLab/vimrc4ssrl)
- [Tutorial for biologists on using the supercomputer at OU-Norman](https://github.com/MooersLab/oscer-supercomputer-tutorial)

## Vim (and Neovim)
- [Vim configuration file](https://github.com/MooersLab/vimrc) Current vimrc file for Mac OSX 10.15
- [Vim configuration file for schooner supercomputer](https://github.com/MooersLab/vimrc4oscer) 
- [Vim configuration file for SSRL SMB cluster](https://github.com/MooersLab/vimrc4ssrl)
- [Neovim configuration file](https://github.com/MooersLab/neovim-init-file)
- [qvim](https://github.com/MooersLab/qvim) Quiz about Vim commands to improve your recall of the commands after a break from using Vim.

## Writing productivity tools
- [The writer's creed](https://github.com/MooersLab/thewriterslaw) Guidelines for greater productivity.
- [Writing Progress tracker by project for 2023 in Excel and Libre Office](https://github.com/MooersLab/writingProgess2023)
- [Writing contract template](https://github.com/MooersLab/writingContract) This contract is in Microsoft Word, markdown, LaTeX, and org-mode.
- [Writing Log template in LaTeX](https://github.com/MooersLab/writingLogTemplate). LaTeX beginers can use this document easily on Overleaf without any configuration.
- [Writing Log template in Org-mode](https://github.com/MooersLab/writingLogTemplateInOrg) Org-mode is a powerful analog of markdown that can interpret LaTeX code blocks. It is vastly more capable than markdown. Org-mode is best edited in Emacs (Sorry, Oveleaf cannot yet work with Org-mode), but VS Code has some support for org-mode files.
- [Emacsconf 2022 talk about GhostText on YouTube, December 2022](https://www.youtube.com/watch?v=2NPUDYAOgW0&t=3s) Includes demonstration of using Emacs to edit a document in Overleaf.
- [TimeSpent](https://github.com/MooersLab/timeSpent) Hourly time tracking by project with Google Sheets. This is useful for making monthly time reports.


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
