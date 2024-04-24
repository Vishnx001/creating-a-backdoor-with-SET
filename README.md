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
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/8a1ae648-c8c8-4138-bc71-68c00421ef48)
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/63a352c2-329f-4852-a14c-4024dddb8c54)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/19b7ad29-8044-4a54-a222-2121bd1dd204)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/6ea6eff5-fb57-4a0b-b41d-b1375a9ccf11)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/62310535-43df-4987-9de3-c10c2a4dfcaa)
It shows the following screen in which the option Google can be selected:
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/9c87c78a-0df0-4032-9aae-075bfb0a6ec4)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/0a8b7d0e-a86f-47ba-9a4a-812500d7a627)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/bfe8ad19-3232-4c0f-a392-e52e9c32eca6)
SET logs the information regarding the Google credentials:
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/71fdc997-06ef-476f-87e2-18f8ce5da048)
SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/22003197/creating-a-backdoor-with-SET/assets/124332243/4231e09c-1112-4e99-a004-26f145a917ea)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
