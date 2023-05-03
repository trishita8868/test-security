# test-security

A reverse shell, also known as a remote shell or “connect-back shell,” takes advantage of the target system’s vulnerabilities to initiate a shell session and then access the victim’s computer. 



![reverse shell demo](https://user-images.githubusercontent.com/107559168/235943259-d216da6e-7cdb-4749-af52-29b2d30da1ef.PNG)

Lets see how a reverse shell program is executed:

1.connects to a remote computer
 
2.redirects the input and output of  target system so the attacker can access it remotely.

3.allows attackers to open ports to the target machines

4.forces communication 
 
5.enables complete takeover of the target machine. 

Now lets have a demo of this:

Scanning ports of target server from attacker Kali Machine


![Port scan](https://user-images.githubusercontent.com/107559168/235944446-defac65d-d524-4f2d-be1d-9636761bc3a0.PNG)



Accessing metasploitable (attacked machine) on Attacker machine

 
![Accessing metasploitable](https://user-images.githubusercontent.com/107559168/235944536-732e61f2-c441-433e-a904-1c585f85c5d2.png)



Running metasploitable service on Kali machine with reverse shell


![hacked](https://user-images.githubusercontent.com/107559168/235943932-c4da10b2-6c48-4e98-950d-808cf34c311b.PNG)

Finally Reverse shell program  redirects the input and output of  target system to attacker host server 




