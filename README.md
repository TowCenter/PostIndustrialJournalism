.tex file manually created from .pdf

generate html w/pandoc:

pandoc PostIndustrialJournalism.tex -o PostIndustrialJournalism.html

Create CMS-ready files:
python CreateRightRail.py PostIndustrialJournalism.html


generate md w/pandoc:

pandoc PostIndustrialJournalism.tex -o PostIndustrialJournalism.md

Generate GitBook files:
python CreateRightRail.py PostIndustrialJournalism.html

OH CHARMS, YOU WORK LIKE THIS!!! :)

