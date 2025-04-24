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

# OUTPUT 

![Screenshot 2025-04-24 205219](https://github.com/user-attachments/assets/a812c4fc-9cea-441a-b26e-d4f6eeaf0cdd)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks.
It displays the following menu and select 2 for Website Attack Vectors:

# OUTPUT 

![image](https://github.com/user-attachments/assets/14e03572-e712-43b9-8eeb-65da6d8a7aee)

The website Attack Vectors displays the following menu. In this menu, 3 for Credential Harvester Attack Method is selected:

# OUTPUT

![424636274-10d04651-ca85-41f4-83d9-168ebba93108](https://github.com/user-attachments/assets/b1665de1-8485-44dc-9b24-bcfd66aaab92)

The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected:

# OUTPUT

![image](https://github.com/user-attachments/assets/71e1ae20-7a6c-43ab-acf2-34f10cb34201)

The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected.
It shows the following screen in which the IP address of the attacker needs to be given (default value):

# OUTPUT

![424637918-e95c8b4b-7fcf-4f07-af23-03e38596c054](https://github.com/user-attachments/assets/67ab2dac-6b30-429f-93c3-35f95218d996)

It shows the following screen in which the option Google can be selected:

# OUTPUT

![424638278-18a611da-b225-4b2f-b8ca-bd24d98de46d](https://github.com/user-attachments/assets/8b2cdd62-97a6-42c6-a5ea-825e06d84ad2)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

# OUTPUT

![424638608-c4577e78-b273-4955-a582-1c9302289934](https://github.com/user-attachments/assets/fc6ab0f9-7058-4c07-a6b9-64ed61b4e0fe)

In Windows IE, on giving the URL http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password.

# OUTPUT

![image](https://github.com/user-attachments/assets/075feddf-095e-4fcc-ad5b-84193be5e6fa)

SET logs the information regarding the Google credentials:

# OUTPUT

![424639524-aed6f0c2-6c9e-44a2-a35a-dcbe20bce335](https://github.com/user-attachments/assets/9d329fcf-9f35-4769-b379-29cda6cda89f)

SET logs the information in the XML file under /root/.set directory:

# OUTPUT

![424643966-19d58cdd-74d6-4467-ad0c-1b676701fc82](https://github.com/user-attachments/assets/eb312bc6-e029-4869-9654-facb179e96bd)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
