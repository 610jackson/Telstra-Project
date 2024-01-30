# Telstra-Project

This job simulation had 4 tasks. 


Task 1. Notifying the correct team of the incident. 
- Looking through the firewall logs, I was able to see that the host was apart of the nbn team.
![image](https://github.com/610jackson/Telstra-Project/assets/106284377/9091f552-671b-43a9-b913-5cfd8f4ba0ae)
![image](https://github.com/610jackson/Telstra-Project/assets/106284377/7ccf4356-6dbe-43f0-b682-cd6a99543aaa)
Using this informaton, I created an email draft to that team with the relevent information.
![image](https://github.com/610jackson/Telstra-Project/assets/106284377/13343b9f-c977-4cf8-81e4-d8a292dcf762)

Task2. Notifying the Networking team. 
- Using previous knowledge from the CCNA and the Firewall Logs, I drafted the email below.
![image](https://github.com/610jackson/Telstra-Project/assets/106284377/f7f664ef-533c-4759-b1b1-7b4488babec0)

Task3. Making the Changes on the Firewall. 
- This task I changed a bit. Since I have very little experience with python, I decided to implement the change at the rounter level using cisco ios.
![image](https://github.com/610jackson/Telstra-Project/assets/106284377/bb8f6485-d996-4b7b-a5a9-327f99c08db0)
I would have applied this to the router closest to the server that was under attack. This should have blocked any traffic from network address the attackers were using. I preteneded it was coming from 1.2.3.4 with a /24 subnet mask. 
I could see them easily getting around this using a different ip address but it may have provided a temporary solution while updating to the newest version provided in the CVE.

Task 4. After action report. 
![image](https://github.com/610jackson/Telstra-Project/assets/106284377/9c7d6a4f-f85d-4cec-a1fc-edb7d0966782)
