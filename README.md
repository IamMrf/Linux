# 1st Step:
#### Open a list of your currently installed programs and Type into Terminal:


      diff dpkg -l 
 
![image](https://github.com/user-attachments/assets/d2b69f66-87ba-4ba0-97dd-73b5af6fad21) 
#### Find the program that you want to uninstall. You'll need to note the official name of the program file rather than the name of the program itself

# 2nd Step:



      Type sudo apt-get --purge remove program



##### make sure to use the program's actual name instead of "program"—and press


### If your program isn't properly removed using the apt-get command, try using instead.
      sudo aptitude remove program
