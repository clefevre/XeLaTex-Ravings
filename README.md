XeLaTex-Ravings
===============

Random Latex Ravings

These are the random notes for my LaTex/XeLaTeX project.

For debian, installing the packages are done via:

sudo apt-get install texlive-full

sudo apt-get install texlive-xetex

Installing fonts should be done as:

sudo cp \<FONTNAME\>.ttf /usr/local/share/fonts

fc-list : fonta family name | grep -i \<FONT\>

The name shown after is the font name that should be used in XeLaTeX to be processed properly. Most of the time this is the same as the fonts filename without the '.ttf'
