# DAT250: Software Technology Experiment Assignment 2 #

Repository for the code used in Experiment 1 & 2: https://github.com/asi96/dat250-jpa-example

## Experiment 1: Application using JPA ##
Code for the following section can be found in the `no.hvl.dat250.jpa.basicexample` and `no.hvl.dat250.jpa.model` package within the linked repository ontop.

Down below are screenshots of the generated tables using Derby's own ij tool

**Verification that the added tables has been succecssfully added to the database (PERSON, PERSON_JOB, JOB, FAMILY):**

![image](https://user-images.githubusercontent.com/31306712/132953558-3c024d0a-2a4f-4a1f-babc-7196510eabee.png)

**A quick look at the person tables data:**

![image](https://user-images.githubusercontent.com/31306712/132953538-034fb9a4-fcbc-4078-9706-cdbd3a86d9af.png)

## Experiment 2: Banking/Credit Card example JPA ##

Code for the following section can be found in the `no.hvl.dat250.jpa.banking` package within the linked repository ontop.

**Confirmation that the new JPA entities has been added to the database:**

![image](https://user-images.githubusercontent.com/31306712/132957617-64129217-7e61-4684-859d-23083bfd1e83.png)


**Confirmation that the dummy data that has been added is also present in the database tables:**

![image](https://user-images.githubusercontent.com/31306712/132957742-05a23111-05ed-445d-a62c-8d8484022581.png)

### Technical problems that you encountered during installation and use of Java Persistence Architecture (JPA) and how you resolved ###
Getting the Derby database to work was a major hassle for me. I was stuck for some time with the program giving me errors when I tried to start it on the command line and I finally found out that the issue was that my JDK installation was too old for the current version of Derby. Once I setup an updated version of JDK the program finally wanted to cooperate. There were still some work to be done getting around understanding how to manuever

### Any pending issues with this assignment that you did not manage to solve ###
The program is working in its current state. I'm a bit unsure, however, if my implementation on Experiment 2 covers everything the domain model outlined.
