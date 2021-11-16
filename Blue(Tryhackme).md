# BLUE

The goal of this room is to deploy and hack into a windows machine, levaraging common misconfiguration issues. 

## Task one: Reconnaissance

It is to be noted that this machine does not respond to ICMP/Ping requests. IT is running Windows 7. 

Scan the machine. (If you are unsure how to tackle this, I recommend checking out the Nmap room)

     Answer: No answer needed
    
How many ports are open with a port number under 1000?

     Command: nmap -Pn <insert machine IP> 
     Answer: 3 
     We use the -Pn flag since the windows machine drops all the ICMP/ping requests hence a normal scan would indicate that the ports are down or otherwise. 
     
What is this machine vulnerable to? (Answer in the form of: ms??-???, ex: ms08-067)
    
     Command: nmap -Pn --script vuln <insert machine IP> 
     Answer: m***-***
     We are using the NSE scripts to scan for the vulnerabilities 
     
## Task two: Gain Access     
  

