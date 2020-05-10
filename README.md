# Spell Checker
- Trie data structure implementation used as a dictionary for spellcheck.
- Data Structures and Algorithms Project
- CSE 2003, Slot B2
- Faculty: Delhi Babu R

### Features
- Adding your own dictionary for spell check
- Adding your own text file for spell checking

### Pre-Requisites
- Clang compiler Installed and added to path
- make installed and added to path

### Instructions to run
- First after extracting, open a terminal inside this folder
- After that type the following
```bash
make
```
- This will run the makefile and compile your program
- Thereafter, you can use the `speller` command with two arguements: First one which is the **relative path to a dictionary** and second one as the **relative path to the text file** you want to check
- Make sure the arguements are paths. For testing purposes, there have been sample dictionaries and sample texts provided in the dictionaries and texts folder
- To run, execute this example command
```bash
./speller "./dictionaries/large" "./texts/alice.txt"
```

### Adding own texts and dictionaries
- To add a text file, simply create a text file and when executing, put its relative path during execution
- To add a dictionary, create a filename with no extension and just add the words, one on each line. Provide the relative path during execution. 

#### Contributors
- Sharanya Mukherjee **19BEC0674**
- Vishakha Kumaresan **19BEC0664**
- Tanisha Rakshit **18BEC0574**