# Tree-CLI-Clone
This is a command line interface to show the "tree" file structure of a given directory. It is a clone of the common "tree" command in Linux. Works as intended on MacOS :)


## Setup

Ensure python 3.9 is installed. Navigate to this directory.

```bash
cd Tree-CLI-Clone/
```

Run tree with a directory path as an argument. The default input directory is the current directory.
```bash
python main.py /your/desired/directory/
```

## Options

```bash 
-v, --version
``` 
shows the application version
```bash
-h, --help
```
shows a list of possible arguments
```bash
-d, --dir-only
```
generates a directory-only tree
```bash
-o, --output-file
```
generates a tree and save it to a file in markdown format
