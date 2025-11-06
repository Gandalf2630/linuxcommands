1# linuxcommands
BANIDT LVL 0

┌──(kali㉿kali)-[~]
└─$ ssh bandit0@bandit.labs.overthewire.org -p 2220 

backend: gibson-1
bandit0@bandit.labs.overthewire.org's password: 

Welcome to OverTheWire!


bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

bandit0@bandit:~$ history
    1  ls
    2  cat readme
    3  history
bandit0@bandit:~$ 



BANDIT LVL 1
┌──(kali㉿kali)-[~]
└─$ ssh bandit01@bandit.labs.overthewire.org -p 2220      

backend: gibson-1
bandit01@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit01@bandit.labs.overthewire.org's password: 

                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ ssh bandit01@bandit.labs.overthewire.org -p 2220

backend: gibson-1
bandit01@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit01@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit01@bandit.labs.overthewire.org's password: 

zsh: suspended  ssh bandit01@bandit.labs.overthewire.org -p 2220
                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ ssh bandit00@bandit.labs.overthewire.org -p 2220

backend: gibson-1
bandit00@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit00@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit00@bandit.labs.overthewire.org's password: 
bandit00@bandit.labs.overthewire.org: Permission denied (publickey,password).
                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ history
    1  ssh bandit@bandit.labs.overthewire.org -p 2220 
    2  ssh bandit0@bandit.labs.overthewire.org -p 2220 
    3  ssh bandit01@bandit.labs.overthewire.org -p 2220 
    4  ssh bandit1@bandit.labs.overthewire.org -p 2220 
    5  setxkbmap dk
    6  ssh bandit1@bandit.labs.overthewire.org -p 2220 
    7  ssh bandit2@bandit.labs.overthewire.org -p 2220 
    8  ssh bandit3@bandit.labs.overthewire.org -p 2220 
    9  ssh bandit4@bandit.labs.overthewire.org -p 2220 
   10  ssh bandit5@bandit.labs.overthewire.org -p 2220 
   11  history
   12  ^[[200~$ history~
   13  history
   14  $ history
   15  HISTTIMEFORMAT="%F %T " && history
   16  history > full_history.txt
   17  history -c
   18  history -m 
   19  history 5
   20  history 1
   21  history
   22  history | grep "ls"
   23  sudo nano .bashrc
   24  ssh bandit01@bandit.labs.overthewire.org -p 2220 
   25  less ~/.bash_history
   26  rm ~/.bash_history && history -c
   27  . ~/.bashrc
   28  \n
   29  history | grep mv
   30  export HISTTIMEFORMAT="%F %T "\n
   31  source ~/.bashrc
   32  history
   33  cat ~/.bash_history
   34  HISTTIMEFORMAT="%F %T " history
   35  history
   36  apt update
   37  sudo apt update
   38  history
   39  # Source - https://stackoverflow.com/questions/15116806/how-can-i-see-all-of-the-bash-history\n# Posted by diveintohacking\n# Retrieved 2025-11-06, License - CC BY-SA 3.0\n\n$ history\n .\n .\n .\n 8720  exit\n 8721  clear\n 8722  history\n
   40  # Source - https://stackoverflow.com/questions/15116806/how-can-i-see-all-of-the-bash-history\n# Posted by etusm\n# Retrieved 2025-11-06, License - CC BY-SA 3.0\n\ncat ~/.bash_history\n
   41  cat ~/.bash_history
   42  # Source - https://stackoverflow.com/questions/15116806/how-can-i-see-all-of-the-bash-history\n# Posted by etusm\n# Retrieved 2025-11-06, License - CC BY-SA 3.0\n\nvim ~/.bash_history \n
   43  ssh bandit01@bandit.labs.overthewire.org -p 2220
   44  ssh bandit00@bandit.labs.overthewire.org -p 2220
                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ history 1000     
    1  ssh bandit@bandit.labs.overthewire.org -p 2220 
    2  ssh bandit0@bandit.labs.overthewire.org -p 2220 
    3  ssh bandit01@bandit.labs.overthewire.org -p 2220 
    4  ssh bandit1@bandit.labs.overthewire.org -p 2220 
    5  setxkbmap dk
    6  ssh bandit1@bandit.labs.overthewire.org -p 2220 
    7  ssh bandit2@bandit.labs.overthewire.org -p 2220 
    8  ssh bandit3@bandit.labs.overthewire.org -p 2220 
    9  ssh bandit4@bandit.labs.overthewire.org -p 2220 
   10  ssh bandit5@bandit.labs.overthewire.org -p 2220 
   11  history
   12  ^[[200~$ history~
   13  history
   14  $ history
   15  HISTTIMEFORMAT="%F %T " && history
   16  history > full_history.txt
   17  history -c
   18  history -m 
   19  history 5
   20  history 1
   21  history
   22  history | grep "ls"
   23  sudo nano .bashrc
   24  ssh bandit01@bandit.labs.overthewire.org -p 2220 
   25  less ~/.bash_history
   26  rm ~/.bash_history && history -c
   27  . ~/.bashrc
   28  \n
   29  history | grep mv
   30  export HISTTIMEFORMAT="%F %T "\n
   31  source ~/.bashrc
   32  history
   33  cat ~/.bash_history
   34  HISTTIMEFORMAT="%F %T " history
   35  history
   36  apt update
   37  sudo apt update
   38  history
   39  # Source - https://stackoverflow.com/questions/15116806/how-can-i-see-all-of-the-bash-history\n# Posted by diveintohacking\n# Retrieved 2025-11-06, License - CC BY-SA 3.0\n\n$ history\n .\n .\n .\n 8720  exit\n 8721  clear\n 8722  history\n
   40  # Source - https://stackoverflow.com/questions/15116806/how-can-i-see-all-of-the-bash-history\n# Posted by etusm\n# Retrieved 2025-11-06, License - CC BY-SA 3.0\n\ncat ~/.bash_history\n
   41  cat ~/.bash_history
   42  # Source - https://stackoverflow.com/questions/15116806/how-can-i-see-all-of-the-bash-history\n# Posted by etusm\n# Retrieved 2025-11-06, License - CC BY-SA 3.0\n\nvim ~/.bash_history \n
   43  ssh bandit01@bandit.labs.overthewire.org -p 2220
   44  ssh bandit00@bandit.labs.overthewire.org -p 2220
   45  history
   46  history 1000
                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ ssh bandit@bandit.labs.overthewire.org -p 2220  
                         _                     _ _ _   
                        | |__   __ _ _ __   __| (_) |_ 
                        | '_ \ / _` | '_ \ / _` | | __|
                        | |_) | (_| | | | | (_| | | |_ 
                        |_.__/ \__,_|_| |_|\__,_|_|\__|
                                                       

                      This is an OverTheWire game server. 
            More information on http://www.overthewire.org/wargames

!!! You are trying to log into this SSH server on port 2220 with a username
!!! that does not match the bandit game.

backend: gibson-1
bandit@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit@bandit.labs.overthewire.org's password: 
bandit@bandit.labs.overthewire.org: Permission denied (publickey,password).
                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ ssh bandit@bandit.labs.overthewire.org -p 2220
backend: gibson-1
bandit@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit@bandit.labs.overthewire.org's password: 

                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ ssh bandit.labs.overthewire.org -p 2220       

backend: gibson-1
kali@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
kali@bandit.labs.overthewire.org's password: 

                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ ssh bandit0@bandit.labs.overthewire.org -p 2220 

backend: gibson-1
bandit0@bandit.labs.overthewire.org's password: 


bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

bandit0@bandit:~$ ^C
bandit0@bandit:~$ exit
logout
Connection to bandit.labs.overthewire.org closed.
                                                                                                                                                                                                                                                                                                  
┌──(kali㉿kali)-[~]
└─$ ssh bandit01@bandit.labs.overthewire.org -p 2220
backend: gibson-1
bandit01@bandit.labs.overthewire.org's password: 
Permission denied, please try again.
bandit01@bandit.labs.overthewire.org's password: 
                                                                                                                                
┌──(kali㉿kali)-[~]
└─$ ssh bandit1@bandit.labs.overthewire.org -p 2220 
backend: gibson-1
bandit1@bandit.labs.overthewire.org's password: 

Welcome to OverTheWire!

bandit1@bandit:~$  an OverTheWire game server. 



