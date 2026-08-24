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
<img width="892" height="550" alt="image" src="https://github.com/user-attachments/assets/2eaa3c52-f1e1-4f7f-8ebc-89524621851b" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="838" height="401" alt="Screenshot 2026-08-24 133833" src="https://github.com/user-attachments/assets/24632628-61e1-4075-8166-8c61cfa2f43d" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="851" height="428" alt="Screenshot 2026-08-24 133955" src="https://github.com/user-attachments/assets/b8d3aa46-dd43-4daa-b0b6-65d1ad994e0a" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="832" height="474" alt="image" src="https://github.com/user-attachments/assets/1f7c3369-80c5-4281-8508-07159c5a3f38" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="861" height="411" alt="image" src="https://github.com/user-attachments/assets/90dd93df-aa19-4327-a3ea-eaf05729f4ae" />



It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="845" height="531" alt="image" src="https://github.com/user-attachments/assets/fb2ff2c4-8f93-422d-a6ed-53ede74159ed" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT


SET logs the information regarding the Google credentials:
## OUTPUT



SET logs the information in the xml file under /root/.set directory:
## OUTPUT












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
