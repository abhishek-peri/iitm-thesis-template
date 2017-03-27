#iitm-thesis-template

A LaTeX class (`iitmdiss.cls`) along with a simple template thesis
(`thesis.tex`) and synopsis (`synopsis.tex`) are provided here.  These can
be used to easily write a thesis (or synopsis) suitable for submission
at IIT Madras.  The class provides options to format PhD, MS,
M.Tech., B.Tech. and DD thesis.  It also allows one to write a synopsis
using the same class file.  Also provided is a BiBTeX style file
(`iitm.bst`) that formats all bibliography entries as per the IITM
format.  A simple sample bibliography file (`refs.bib`) is also
provided.

Please read thesis.dvi for more details.


Prabhu Ramachandran <prabhu@ae.iitm.ac.in>

(modified by Shahidh K Muhammed <shahidhkmuhammed@gmail.com>)

## Instructions

- Install TexLive:
  - Generic: http://www.tug.org/texlive/acquire-netinstall.html
  - Ubuntu:  `sudo apt-get install texlive-full`
- Edit `thesis.tex` file using any text editor.
  - TeXStudio preferred: http://www.texstudio.org/
  - Install on Ubuntu: `sudo apt-get install texstudio`
- Compile the tex file to pdf using terminal/command line, execute:
  - `pdflatex thesis.tex`
- You can use any other LaTeX installation of your choice, but `TexLive Full` install will guarantee that all required packages are installed.
- In case you are having trouble using LaTeX on your machine, simply create an account at https://www.sharelatex.com/ and create a new project and upload a zip of this project.
  - zip file available at https://github.com/The-WebOps-Club/iitm-thesis-template/archive/master.zip
