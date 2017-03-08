# bash-scripts
This is a random collection of useful shell scripts that I have accumulated over time. To use them, make sure you mark them as executable and place them in a folder on the path. My preferred location is ~/bin/.

* **`compiler`:** Script to compile LaTeX files into PDFs. Syntax is `compiler myfile.tex` which produces `myfile.pdf` in the working directory.
* **`ducustom`:** Custom disk usage that displays files sorted by size (largest to smallest) with arbitrary folder depth, e.g. `ducustom 2` lists all files and directories in the current folder as well as its subfolder. Helpful for finding large files.
* **`find_replace_in_files`:** Find and replace text in all files of a (set of) directories. Useful if workflow is dependent on file paths, and you just migrated servers.
* **`git_find_big`:** Find large files in a git tree. Found [http://stackoverflow.com/questions/10622179/how-to-find-identify-large-files-commits-in-git-history](here).
* **`pdf2eps`:** Convert PDF files to EPS format. Found [http://tex.stackexchange.com/questions/20883/how-to-convert-pdf-to-eps](here).
* **`ps2eps`:** Convert PS files to EPS format (i.e. "encapsulate" them). Found [http://aty.sdsu.edu/~aty/bibliog/latex/PSandEPS.html](here).
* **`shellexec`:** Submit a generic shell script using `nohup`.
* **`statampbatch`:** Sample SLURM script for running a program in Stata-MP. Note that SLURM configurations differ by server, so check with your admin before attempting to use this.
* **`*hup`:** Commands for running scripts for various statistical analysis programs using `nohup`. Includes capabilities for R, Julia, Stata, SAS, and Matlab.

Finally, many of these files were created with the help of @jaredashworth, so I acknowledge his help.