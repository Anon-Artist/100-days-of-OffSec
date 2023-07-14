# Building an Active Directory Lab

### Checklist for setting up a basic active directory lab

Step 1: For setting up an active directory lab first you need to construct an idea or a story. My idea was based on Sherlock Holmes. so that my domain name was sherlock.corp and my usernames were sherlock.holmes, john.watson, jim.moriarty etc.. Trust me it will be fun.

Step 2: Install virtual box.

Step 3: Download and Install Windows Server 2018 or 2022 and Windows 10 or 11. Server will be promoted to Domain Controllers and Windows 10 will be used as workstation.

Step 4: Change the Hostnames.

Step 5: Assign static IP address to machines.

Step 6: Install Active Directory Domain Service on Windows Server and after that promote it to Active Directory Domain Controller.

Step 7: Add the Forest and set DSRM Password and complete the process.

Step 8: Create new Users and Domain Users set privileges appropriately.

Step 9: Add more functionality according to the need such as ADFS, ADCS, Webservers etc.

### How to setup an Active Directory Lab

There are lot of resources available in internet to learn how to setup a basic to advanced active directory lab for offensive and defensive operations.\
My first active directory lab was developed with the help of Practical Ethical Hacking course by The Cyber Mentor. If you don't have this course don't worry, that particular video is available on his Youtube channel and you can access via this link [https://www.youtube.com/watch?v=xftEuVQ7kY0](https://www.youtube.com/watch?v=xftEuVQ7kY0)&#x20;

From this video you will get a brief idea about developing an AD lab at home.\
Another reference is [https://macrosec.tech/index.php/2021/07/19/building-a-basic-active-directory-lab/](https://macrosec.tech/index.php/2021/07/19/building-a-basic-active-directory-lab/)

### Building a Vulnerable Active Directory Lab

There are several resources available in the internet. Here are some curated resource for setting up a vulnerable AD lab.\
I recommend to make your lab vulnerable by yourself without relaying on the scripts so that you will learn how to defend them too on the other hand you can save time by using the scripts

1. [https://github.com/Orange-Cyberdefense/GOAD](https://macrosec.tech/index.php/2021/07/19/building-a-basic-active-directory-lab/)
2. [https://github.com/davidprowe/BadBlood](https://github.com/davidprowe/BadBlood)
3. [https://github.com/dievus/ADGenerator](https://github.com/dievus/ADGenerator)
4. [https://github.com/WazeHell/vulnerable-AD](https://github.com/WazeHell/vulnerable-AD)
