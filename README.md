# Tidy projects

This repository is a workshop/tutorial where attendees play the part of "new research group members", who receive a zip file for a former project/lab team member, and are needing to use this information to start working in their new role.

The zip file contains:

- data
- script(s) (maybe a .R file)
- results derived from using the script
- a Word document containing some kind of report/commentary 
- some notes relating to the data that have been used

Your task is to:

 - download [`rnaseq.tar.gz`](https://github.com/murraycadzow/tidy-projects/raw/project_creation/rnaseq.tar.gz)
 - investigate the contents of the files
    - do the files match the contents of the analysis?
    - what are some of the problems you came across?
- organise the contents into a "tidy" project structure
    - separate code, data, results
- improve the repository
    - add documentation
    - include metadata
    - update the analysis
- think about how you could make this analysis and data shareable
 
    
Data download link: [`rnaseq.tar.gz`](https://github.com/murraycadzow/tidy-projects/raw/project_creation/rnaseq.tar.gz)


This exercise can be done either locally or on NeSI in the Jupyter notebooks bash terminal if you wish.

```.bash
# download the file on the commandline
wget https://github.com/murraycadzow/tidy-projects/raw/project_creation/rnaseq.tar.gz

#extract the tar archive
tar -xzf rnaseq.tar.gz
```
