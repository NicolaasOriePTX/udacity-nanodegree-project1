# udacity-nanodegree-project1

First udacity nanodegree project; writing a blog and create repo.

For the Medium post associated with this repo, please visit: https://medium.com/@nicolaasorie/do-managers-make-more-in-software-development-1a42cfe5e27b

This code contains a quick analysis on the stackoverflow developers survey 2022 results. It answers the following research questions:

1) Do people managers make more money than single contributer
2) Does working experience determine salary
3) Do people managers make more money than single contributer, irrespective of their working experience

To run : run the main.ipynb file

**files**
.gitignore : ignored local files
main.ipynb : main code
readme.md  : project explanation

in /data
README_2022.txt         : dataset information
Research questions      : explanation of research questions


**Libraries**
numpy==1.23.5
matplotlib==3.6.3
seaborn==0.11.2
scipy==1.7.1
pandas==1.5.3

**Main results**
1) Do people managers make more money than single contributer : True: significant difference in PM's and IC's mean yearly salary
2) Does working experience determine salary : False: no significant correlation between working experience and salary
3) Do people managers make more money than single contributer, irrespective of their working experience : False: no significant difference between salaries of PM's and IC's within the same work experience group

**Acknowledgement**
dataset credit: Stackoverflow developers survey 2022