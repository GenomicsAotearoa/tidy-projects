Time allotted: 1 hour

# Tidy projects


This repository is a workshop/tutorial where attendees play the part of "new research group members", who receive a zip file for a former project/lab team member, and are needing to use this information to start working in their new role.

The exercise in this workshop is designed as a practical implementation of the presentation from the [Genomic Aotearoa Good Practice Workshop](https://github.com/GenomicsAotearoa/ga-good-practice).


The compressed tar file contains:

- data
- script(s) (python: *.py, R: *.R, bash: *.sh, slurm: *.sl )
- results derived from using the script
- a Word document containing some kind of report/commentary 
- some notes relating to the data that have been used

This workshop can be done either locally or on [NeSI in the Jupyter notebooks](https://jupyter.nesi.org.nz/hub/login?next=/hub/) bash terminal if you wish.

Your task is to:

## 1. Download [`rnaseq.tar.gz`](https://github.com/murraycadzow/tidy-projects/raw/project_creation/rnaseq.tar.gz) (5 min exercise)


**Data download link:** [`rnaseq.tar.gz`](https://github.com/murraycadzow/tidy-projects/raw/project_creation/rnaseq.tar.gz)

```bash
# This code block relates to if you are doing this on NeSI

# change into the workshop directory
cd /nesi/nobackup/nesi02659/tidy-projects

# create then move into a directory for your username
mkdir $(whoami)
cd $(whomai)
```


Download and extract the data
```bash
# download the file on the commandline
wget https://github.com/murraycadzow/tidy-projects/raw/project_creation/rnaseq.tar.gz

# extract the tar archive
tar -xzf rnaseq.tar.gz
cd rnaseq/
```

## 2. Investigate the contents of the files (10 min exercise, 5 min discussion)
   
- Do the files match the contents of the analysis?
- What are some of the problems you came across?

_Pause for discussion_


## 3. Improve the repository (15 min exercise, 5 min discussion)
   
- (optional) implement version control on the directory and track the changes you make
- separate code, data, results
- add documentation
- (optional) convert analysis/documentation into a markdown (or Rmarkdown) document
   - include metadata
- update the analysis
- anything else?

## 4. Think about how you could make this analysis and data shareable (10-15 min discussion)
   
- what are some considerations for the code, analysis, and data?

_Pause for discussion_

## 5. (optional) Apply the concepts of tidy projects to one of your existing projects    

Have a go at tidying up one of your existing projects.



