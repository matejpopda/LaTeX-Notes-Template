# LateX-Notes-Template

Template repository for taking notes in my classes in LaTeX, with the resulting pdf getting published to github pages.

What goes where?

- main.tex - Mainly command definitions and package imports, only links subfiles.
- images/ - dump of all images
- hw/ - for homework subfiles
- notes/ - for notes subfiles

.gitignore is configured to ignore all files (including pdfs) those get deployed to github pages, and uploaded as an artifact with the workflow in the .github folder.

 For use in english just remove the babel package and change some of the math environments (all defined in main.tex)