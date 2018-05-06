<!--Markdown Image Format could not be used, for image would not display on website-->
<a href="https://github.com/harens/PonySh">
<img src="PonyShLogo.png" alt="PonySh Logo">
</a>

<a href="https://github.com/harens/PyPony">
<img src="PyPonyLogo.png" alt="PyPony Logo">
</a>

## ThePonyInformationProject
[![Creative Project](https://img.shields.io/badge/Creative-Project-<COLOR>.svg)](https://github.com/harens/CreativeProject)

The Pony Information Project aims to educate all about ponies. It now comes in three different forms, the [Website](https://harens.github.io/ThePonyInformationProject/), [PonySh](https://github.com/harens/PonySh), and [PyPony](https://github.com/harens/PyPony). PonySh and PyPony were custom-made for the Creative Project.

<!--Markdown Image Format could not be used, for image would not display on website-->
<img src="PonyTerminal.png" alt="The Pony Information Project Shell Edition">

### Inspiration

#### Website

I decided to build The Pony Information Project (then known under a different name) since we were learning about HTML and CSS in class. The idea of writing about ponies may seem entirely random, but even though I've never ridden a horse/pony before, I have always found them quite exciting animals.

#### PonySh

For the Creative Project, I was at first unsure of what to do. I considered writing an application in [Swift](https://swift.org), but this would take too long. I thought about building another website, but I already had a lot of experience with this and wanted to try something different.

The idea of doing a scripting language came after I played a few retro games in the terminal. It's pretty easy to do on Mac OS. First, you type:

```
emacs
```
_Note: To anyone who's interested, GNU Emacs is a very interesting text editor. You can find out more [here](https://www.gnu.org/software/emacs/)_

Then, you hit the escape key, press x, and then enter a game.

I then realised that bringing ponies to the terminal is undoubtedly an original idea, and was very well possible within the time range.

There are numerous scripting languages that one can use. The most obvious choice would be [Python](https://www.python.org). However, for me, Python didn't seem creative enough. At the other end of the spectrum, you have less popular choices such as [REXX](http://www.rexxla.org) and [Tcl](https://www.tcl.tk), but they would take too long to learn. That is why I chose [Shell](https://www.gnu.org/software/bash/), a language I knew already, and that was only somewhat popular.

Choosing the theme for the scripts was a simple choice since I had already done a website on ponies.

#### PyPony

I finished PonySh much, much earlier than expected. I was thinking about integrating it with [MakeFile](https://www.gnu.org/software/make/manual/make.html), but I realised that it would be much more beneficial to do Python. Though I felt that it would not be a very creative choice for this Creative Project, there were three main reasons why I chose to do this:

1. The school blocks the command line (and I completely understand why), so there is no easy way to demonstrate the project in front of the class.
2. My partner does not know Shell, HTML or CSS. However, he can code a bit of Python.
3. In the long run, Python is an arguably more valuable language than Shell (unless you use UNIX-like systems a lot). Therefore, this project would be good practice.

### Timeline

Due to practicality reasons, all three versions moved about a lot. For this reason **I apologise sincerely**. I've tried my best to link together all the commits, but it is not perfect.

#### Website

Unfortunately, the commits have been corrupted by my poor decision to merge all the files _from all versions_ in the master branch (the original home of the website). Again, I apologise for this. For the gh-pages branch, where it got moved to, please click [here](https://github.com/harens/ThePonyInformationProject/commits/gh-pages).

#### PonySh

PonySh got moved three times in total, as well as having a name change along the way.

* Click [here](https://github.com/harens/PonyInfoGuide-ShellEdition/commits/master) for the first 90 commits of the Shell Edition. I updated this repo between the 28th and the 30th of April.
* Click [here](https://github.com/harens/ThePonyInformationProject/commits/Shell-Edition) for the commits of the Shell Edition branch.
* Click [here](https://github.com/harens/PonySh/commits/master) for the PonySh repository.

#### PyPony

Due to this version being the newest of the three, it only got moved twice. Somehow or another, its name also got changed though.

* For the Python Edition branch, click [here](https://github.com/harens/ThePonyInformationProject/commits/Python-Edition).
* For the PyPony repository, click [here](https://github.com/harens/PyPony/commits/master).

#### Blog

Unfortunately, the only part of The Pony Information Project that has a clear set of commits is the blog. Click [here](https://github.com/harens/CreativeProject/commits/master).

### Languages Utilised

#### Website
* **[HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)** - HTML is used to provide the foundations of the website.
* **[CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)** - Used to present the website.
* **[Javascript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)** - Only used for one 'back-to-top' button. Reason being is that I do not know the language that well.

#### PonySh
* **[Shell](https://www.gnu.org/software/bash/)** - Shell scripts (or more specifically, [bash scripts](https://www.gnu.org/software/bash/)) were used to build PonySh.

#### PyPony
* **[Python](https://www.python.org)** - The only language used in PyPony.

### General

* **[Git](https://git-scm.com)** - Git was used to push, pull and fetch from [GitHub](https://www.github.com).
* **[GFM](https://github.github.com/gfm/)** - I used Github-Flavoured Markdown for any form of write-up. One notable example of its use is in the making of this very website!

### Programs Used

* **[iTerm2](https://www.iterm2.com)** - MacOS terminal emulator used to test PonySh.
* **[Atom](https://atom.io)** - The main text editor that was used. It was utilised to edit all versions of The Pony Information Project.
*  **[GitKraken](https://www.gitkraken.com)** - Though it is possible to pull, push and fetch from Atom, this was the preferred program of choice. Originally, [GitHub Desktop](https://desktop.github.com) was used, though this was before I got the [Student Developer Pack](https://education.github.com/pack), which included a pro GitKraken account.
* **[Vim](https://www.vim.org)** - Vim was used to create and edit small testing files quickly from the terminal, without having to launch Atom.
* **[Travis CI](https://travis-ci.org)** - Travis CI was used to test and deploy builds.
* **[GitHub](https://github.com)** - GitHub was used to host all three versions.

### Operating Systems Tested On

The Pony Information Project was tested on three UNIX-like Systems:

* **[MacOS Sierra](https://www.apple.com/lae/macos/high-sierra/)**
* **[Debian 9](https://www.debian.org)** (Stretch)
* **[Ubuntu 14.04.05 LTS](https://www.ubuntu.com)** (Trusty) - Tested from Travis CI using the Trusty Build Environment

### Sources and Acknowledgements
Any references and honourable mentions are found [here](https://github.com/harens/ThePonyInformationProject/tree/master#contributors-and-resources).

### Other
For more information about this The Pony Information Project, please click [here](https://github.com/harens/ThePonyInformationProject/tree/master#the-pony-information-project-).
