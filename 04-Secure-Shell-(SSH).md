- To access the Bandit CTF games, we must "ssh" or remotely access the game machine
- The standard port for SSH is 22, however, SSH can be set up on any port
## Basic Syntax
```ssh fred@fred-computer```
- The command "ssh" tells your terminal that you are using the ssh command
- In this case, you are trying to log in with the username "fred" and log into a computer named "fred-computer"
```ssh fred@192.168.1.12```
- Instead of a computer name, you can specify an IP address instead
```ssh -p 2222 fred@192.168.1.12```
- If SSH is running on a different port than 22, you would specify that port with the ```-p``` flag. In this case, we are specifying port 2222
*Note: In the Bandit CTF, you will be prompted for a password. When you type, however, you will not see any indication that your password is being entered. This is typical in SSH. Do not worry, your password is being entered.*

---
# SSH Quiz
1. Access the Level 0 instructions for the Bandit CTF at https://overthewire.org/wargames/bandit/bandit0.html
2. What is the correct syntax to log into bandit0?
3. Log into bandit0 to start the CTF