## Metasploit
This is a walkthrough the introduction to metasploit room. It is not a fully comprehensive room hence more reading is required. 

## Task one: Introduction 
Metasploit, an open-source pentesting framework, is a powerful tool utilized by security engineers around the world. Maintained by Rapid 7, Metasploit is a collection of not only thoroughly tested exploits but also auxiliary and post-exploitation tools. Throughout this room, we will explore the basics of using this massive framework and a few of the modules it includes. 

Kali and most other security distributions of Linux include Metasploit by default. If you are using a different distribution of Linux, verify that you have it installed or install it from the Rapid 7 Github repository. 

    Answer: No answer needed
    
## Task two: Initializing...

First things first, we need to initialize the database! Let's do that now with the command: msfdb init
If you're using the AttackBox, you don't need to do this.
    
    Answer: No answer needed
    Command: msfdb init


Before starting Metasploit, we can view some of the advanced options we can trigger for starting the console. Check these out now by using the command: msfconsole -h

    Answer: No answer needed
    Command: msfconsole -h
    
We can start the Metasploit console on the command line without showing the banner or any startup information as well. What switch do we add to msfconsole to start it without showing this information? This will include the '-'

    Answer: -q 
    This means that metasploit will start quielty without the banner(art) or info
   
Once the database is initialized, go ahead and start Metasploit via the command: msfconsole

    Answer: NO answer needed
    Command: msfconsole
   
After Metasploit has started, let's go ahead and check that we've connected to the database. Do this now with the command: db_status

    Answer: No answer needed 
    In the output make sure you are connected to a database
    
Cool! We've connected to the database, which type of database does Metasploit 5 use? 

    Answer: postgresql 
    Command: db_status
## Task three: Rock 'em to the core[commands] 
