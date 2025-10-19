# Part A
## 1. Start a VS Code session at OSC in the folder /fs/ess/PAS2880/users/$USER. Create a new dir for this assignment, /fs/ess/PAS2880/users/$USER/GA4, and switch to that folder in VS Code using the “Open Folder” option. This should be your working dir for the entire assignment.
I used the following command:
```bash
mkdir -p GA4
```
Open Folder: fs/ess/PAS2880/users/dengyaxin1156/GA4
## 2. Initialize a Git repository. Commit to the repo throughout the assignment as you see fit, but at least once for each “Part” of this assignment. Use and commit a .gitignore file as appropriate. (Tip: Many of you would do well to recall the feedback you got on your Git repo from the previous assignment!)
I used the following command:
```bash
git init
git config user.name "git@github.com:Yaxin-Deng/GA4-dengyaxin1156.git"
git config user.email ""
```
## 3. Inside dir GA4, create a README.md file and open it in the VS Code editor. Use this file throughout the assigment to add your answers where appropriate.
I used the following command:
```bash
touch README.md
```
## 4. Inside dir GA4, also create dirs scripts and results. We’ll make your dir self-contained again (like a typical situation for a research project) by copying some data into it:
I used the following  command:
``` bash
mkdir -p scripts results
ls
cp -rv ../garrigos-data/fastq data
```
The output was:
README.md  results  scripts
# GA4-dengyaxin1156
