
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
## OUTPUT
<img width="1406" height="777" alt="Screenshot 2026-08-25 135308" src="https://github.com/user-attachments/assets/eb9253fa-d643-4549-838a-110089340b52" />
<img width="1302" height="1021" alt="Screenshot 2026-08-25 135322" src="https://github.com/user-attachments/assets/1d19b5d0-7e52-4d9b-aba4-bad2181a044a" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1360" height="1015" alt="Screenshot 2026-08-25 135329" src="https://github.com/user-attachments/assets/ce330e0e-4878-43e5-818f-58b182d30b77" />

<img width="1266" height="1020" alt="Screenshot 2026-08-25 135404" src="https://github.com/user-attachments/assets/46beda0c-4c8d-4d21-ba3f-5138a224f7b9" />

It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="1395" height="1055" alt="Screenshot 2026-08-25 135418" src="https://github.com/user-attachments/assets/ad3012cf-eb07-4ca6-b8a8-bdef217c47d6" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1422" height="1033" alt="Screenshot 2026-08-25 135442" src="https://github.com/user-attachments/assets/15e791c5-bd22-4efa-af5b-dd58bba69827" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="937" height="842" alt="Screenshot 2026-08-25 135716" src="https://github.com/user-attachments/assets/a15c72f5-b0de-49ca-ad0b-2aab6659f876" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="977" height="447" alt="Screenshot 2026-08-25 135802" src="https://github.com/user-attachments/assets/912d2992-63f7-41a7-9e81-b29a7fdaa92a" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT


<img width="975" height="293" alt="Screenshot 2026-08-25 135834" src="https://github.com/user-attachments/assets/32112210-7cd0-4bb4-abef-78ffa34c2685" />


In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="951" height="1078" alt="Screenshot 2026-08-25 140530" src="https://github.com/user-attachments/assets/bff2211d-83b1-4bb5-a8b1-fb5eddd7142e" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="951" height="1078" alt="Screenshot 2026-08-25 140530" src="https://github.com/user-attachments/assets/3085f990-0981-4ec7-b096-54e8b0d09da1" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="943" height="1013" alt="Screenshot 2026-08-25 140642" src="https://github.com/user-attachments/assets/9075e138-9f09-426f-a679-d25bd12ea0db" />











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
