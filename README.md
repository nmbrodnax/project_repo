# Sample Project Repository

## Project Directory Structure

code/  
data/  
draft/
img/
README.md  
.gitignore  

## Instructions
### code
Store your scripts (.R, .py, .ipynb, .sh, etc.) in this directory.  Before pushing your changes to the repository, be certain that your scripts do not contain any data or credentials such as passwords or API keys.  Your scripts should also contain only relative paths, as absolute paths are machine specific and will not work on anyone's computer but yours.

### data
Store your data (.csv, .txt, .xlsx, .dat, etc.) in this directory. Do not push data files to the repository.  In fact, this repository does not contain a data directory because the .gitignore file ignores data folders by default!  You can create the data directory using your file browser or by typing `mkdir data` on the command line from within the root folder of the repository. There are two sections with special emphasis:

 * **DATA** - this section will ignore any directory named "data/" and will ignore several common data file extensions
 * **AUTHENTICATION** - this section will ignore any text file ending with "_auth.txt."  For example, if you want to ignore your local API key for the Google Geocoding API, you would create a text file something like "geo_auth.txt" and save your API key in that file.  Then, within your API script, simply load the key into memory by opening and reading the contents of your file and saving the contents to a variable. 

### draft
If you are using LaTeX, store your text documents (.tex) in this directory.  This can include files for papers or posters.

### img
Store your images (.png, .jpg, etc.) in this directory.  If you save all images in one place, they will be easier to reference within your LaTeX file (if you are using LaTeX).

## Special Files
### README.md
This file will provide the front page to your repository.  Use it to provide a basic description of the project as well as other pertinent information.

### template.gitignore
This file contains filenames, directory names, and file extensions that should be ignored by Git.  To activate it, rename the file from `template.gitignore` to `.gitignore`. 