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
![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/8c827a2b-05fb-41f6-ba07-621cfea82fde)

It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/45772e56-93f2-400f-b7bc-a1c3118626be)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/8d96dae3-dccd-496b-ab0c-951b3330c05d)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/962de68e-e50f-44a5-86d0-24892055a68f)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/ab191624-8d61-40d2-ae31-226db434f86d)

It shows the following screen in which the option Google can be selected:
![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/366eab67-2b88-4ae9-b039-3512740927a0)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/b27ca191-255e-448e-ab61-f93db5a0100b)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/c332b60c-11cd-4fbd-9575-7f52a836185f)
SET logs the information regarding the Google credentials:
![image](https://github.com/Shobika187/creating-a-backdoor-with-SET/assets/94508142/dda3d656-bb1b-4bc3-a7b3-10b3fd6bd530)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
