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
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
<img width="1033" height="540" alt="exp 7 1st" src="https://github.com/user-attachments/assets/ac9a6cc8-338a-4a4b-976b-e2292c0a0121" />

## OUTPUT
It displays the following menu and select 2 for Website Attack Vectors:
<img width="1033" height="537" alt="exp 7 2nd" src="https://github.com/user-attachments/assets/82148fc4-f335-4f0f-bba3-d5a56650add7" />

## OUTPUT
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
<img width="1032" height="545" alt="exp 7 3rd" src="https://github.com/user-attachments/assets/1fb6f17e-0bd8-42af-9992-8f549a077e54" />

## OUTPUT
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
<img width="1026" height="538" alt="exp 7 4th" src="https://github.com/user-attachments/assets/2540ba2e-c9c3-4417-add0-fea4b9fc128f" />

## OUTPUT
It shows the following screen in which the option Google can be selected:
<img width="1031" height="537" alt="exp 7 5th" src="https://github.com/user-attachments/assets/87e966b9-31ee-4db4-a8e3-fe6056496e61" />

## OUTPUT
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
<img width="1036" height="542" alt="exp 7 6th" src="https://github.com/user-attachments/assets/9d896f29-d5f7-4d25-9ccf-cae015d6633c" />

## OUTPUT
In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
<img width="1028" height="537" alt="exp 7 7th" src="https://github.com/user-attachments/assets/d8829c6c-af5e-4fd9-9b3b-a6fe09bd3e84" />

## OUTPUT
SET logs the information regarding the Google credentials:
<img width="547" height="898" alt="exp 7 8th" src="https://github.com/user-attachments/assets/b2a77fcd-f1a2-40c1-9360-c57790b03f6e" />

## OUTPUT
SET logs the information in the xml file under /root/.set directory:
<img width="823" height="140" alt="exp 7 9th" src="https://github.com/user-attachments/assets/533f691f-9786-4a0b-923c-2d8360d69f51" />

## OUTPUT
<img width="827" height="428" alt="exp 7 10th" src="https://github.com/user-attachments/assets/8c923100-213f-4cfd-95b6-843174701fa3" />












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
