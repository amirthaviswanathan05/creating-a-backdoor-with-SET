## AMIRTHAVARSHINI V
## 212223040014
# Creating-a-backdoor-with-SET
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

![setoolkit](img/setoolkit.png)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

![set1](img/set1.png)

It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

![set2](img/set2.png)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

![set3](img/set3.png)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

![web_attack_1](img/set_webattack1.png)


It shows the following screen in which the option Google can be selected:
## OUTPUT

![set_webattack_template](img/set_webattack_template.png)



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

![ipaddress](img/ipaddress.png)


In windows IE, on giving the url http://10.188.150.223/ (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

![goole.com](img/google.com.png)

SET logs the information regarding the Google credentials:
SET logs the information in the xml file under /root/.set directory
## OUTPUT

![username_password](img/username_pass.png)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
