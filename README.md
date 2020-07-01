# Analytics Assignment BE June - July 2020
Repo to contain instructions/files for a small BE assignment for CFR Analytics Full Stack Role.

## Goal
The goal of this assignment is to transform a simplistic OLTP database into a new OLAP database. This
OLAP database should be designed keeping in mind the requirements as provided in the companion Front End assignment.

## Set up instructions
Run the script in `scripts.sql` on a postgresql environment and explore the data.

## Additional Information
As can be observed from the scripts, Departments have Teams which in turn have Users. Every User can create an objective.
Every Objective can have key results associated with them. An objective is complete only AND only if all the key results
associated with it have a status of `Completed`.

Please review the code to understand the relationship between the entities.

## Assignment Guideline
This is a minimalistic example. When transforming the OLTP to OLAP, please keep in mind that tables may have much more information
than is presented in the scripts. They could have additional fields as well. It will be beneficial to align the transformation to 
achieve the companion FE assignment's objectives.
