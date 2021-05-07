# DevOps Assignment

## Introduction
This repository holds the DevOps assignment. 

## The assignment
As developers of this beautiful service, of course, we need proper CI/CD! We suggest GitLab with GitLab runner since it is what we use in production. You can create a free account at [https://gitlab.com/](https://gitlab.com/). _**as pubilc repo, group name as "Demo1" and Project name should be "DemoCICD"**_

There are a couple of requirements:
- [ ] Write a bash script **gencsv.sh** to generate a file named **inputFile** whose content looks like as below and upload to gitlab project **DemoCICD**:
```
    0, 234
    1, 98
    2, 34
```
    These are comma separated values with index and a random number.
    Running the script without any arguments, should generate the file inputFile with 10 such entries in current directory.
    You should be able to extend this script to generate any number of entries, for example 100000 entries.
    Run the script to generate the inputFile. Make sure that the generated file is readable by other users.
- [ ] Write a gitlab pipeline(.gitlab-ci.yaml) with executing **gencsv.sh** script and print the output of script in pipeline.

## Questions
If you have any questions about the assignment, the project setup or you're simply stuck, feel free to contact us at <a href='mailto:muralikrishna_r@hcl.com'>muralikrishna_r@hcl.com</a> and <a href='mailto:alluri_s@hcl.com'>alluri_s@hcl.com</a>. 

Good luck with the assignment!
