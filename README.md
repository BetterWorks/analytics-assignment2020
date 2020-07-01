# analytics-assignment2020
Repo to contain instructions/files for a small BE assignment for CFR Analytics Full Stack Role.

## Goal
You are asked to implement the BE so as to support a dashboard as shown in this image https://drive.google.com/file/d/12Zq9aBHvnwiZJt-QU6f6WXu1rYJD-JEn/view .

Your implementation must focus on just the Objectives on track card and the details section it shows on clicking. The Objectives recently updated and Placeholder KPIs can be ignored totally.

Clicking on a section in the Objectives on track will show the teams within that department as shown in this screenshot https://drive.google.com/file/d/1qMvBFoK__MT6jmAUlzADe1ib3suwqI-T/view .

### You are required to implement ATLEAST one of the following:

* A database schema transformation that supports easier analytical processing of recorded transactional data. The schema as it stands ( refer to `scripts.sql`) can be better transformed to suit analytical requirements although it is a minimalistic example. Feel free to manipulate the existing implementation and come up with a consistent schema to support this objective. If you choose to attempt this without the second task ( below ), please be sure to implement this transformation using `python` . You can read the data from the database after running `scripts.sql` and import it as `JSON` . The final output transformation should as well be in `JSON` using a `python` script. We're looking for your understanding of data-modelling here, alongwith some nice object oriented Python to get the job done.

* A Restful BE designed in Django with essential end points to serve data for a FE that displays the above pictured dashboard. The BE will be required to access a Postgresql DB. Feel free to go through `scripts.sql` to get a basic idea of the entities and their relationships. You can even implement your own data model based off the tables as provided in `scripts.sql`. This task only requires that you read from a postgresql database & provide meaningful data rest-fully to a FE. We're really looking for object oriented code & nice separation of concerns here !

#### Nice to haves ( as applicable to the above tasks ) ! :

* Schema diagram for the transformation in DB ( if not the transformation itself ! )
* Tests for the BE
* Documentation for the API

Please include a README.md file in your Github repo detailing the following:

* What has been completed
* What is not completed
* Deployment steps
* Known bugs and limitations

### Evaluation criteria

Transformed schema design ( first task if applicable )
Restful Implementation of API ( second task if applicable )
How production ready is your code
Adherence of the implementation to the design

## Assignment Guideline for DB transformation
This is a minimalistic example. When transforming the transactional data ( provided ) to an analytical one, please keep in mind that tables may have much more information than is presented in the scripts. They could have additional fields as well. It will be beneficial to align the transformation to achieve the FE dashboard's requirements as seen in the screenshots.
