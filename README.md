# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/61a45236-82c4-44ae-abf8-7d4e41305c03)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/3afff066-28a2-444e-be21-9b82f4202bbb)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/094e09a6-6f57-44e3-9411-68769e33183f)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/40093350-3f85-4cc7-b047-eeb91f40e898)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/0d5b25f3-4a50-49e8-8e27-f60c4659a102)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/e7f1d4b2-c332-4305-8521-da097db03147)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/3c134da5-3df0-44c9-8752-5cbb528803a9)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/8c96400d-b5c2-4a93-a7d7-aa71284bb7cc)

![image](https://github.com/R-Guruprasad/creating-a-backdoor-with-SET/assets/119390308/353709b4-a60e-450e-b648-938e77f9fa24)

SET logs the information regarding the Google credentials:


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
