# cryptonite1
cryptonite taskphase 1
Linux fundamentals-1
Started linux basic fundamentals -1 
Learnt basic commands :echo , whoami, ls , cd, cat , pwd ,find , grep , &,&&,>,>>
Ls- listing
Cd-change directory 
Cat-concatenate 
Pwd-print looking directory 
Find - will find folder name 
&-allows to run commands in the background 
&&- to make a list of commands 
>- send output to somewhere else 
>>-just puts output at the end of the file 

Linux fundamentals-2
Started linux fundamentals-2 from thm (try hack me) 
Learnt abt ssh, flags and switches (to extend behaviour of commands ) 
ls, -a(short for –all) 
Man command 
Touch  ,Mkdir, cp,mv, rm , file  


Went to over the wire and started with bandit







Linux fundamentals -3 
Learned commands like : Nano, VIM, wget, SCP, ps, top, kill, systemct1, ps aux, fg, cron, add-apt-repository, apt, apt update and add-apt.

 level 0 :
<img width="904" alt="image2" src="https://user-images.githubusercontent.com/120416962/217062262-2b21858f-82a4-4327-bf75-b1e6f07afda5.png">









USING SSH command to log in and use ls to see what is there in the directory 
Opening readme using cat  to see what is there inside the file 
 We got the password for level 1 from level 0 
Level 1:



We use ls to see what's in the directory 
Cat - doesnt work 
ctr+d to get out 
Password from level 1 to go to level 2 

 Level 2:
Ls -a  to view all files 
Using cat command opened “spaces in this filename ”
We get password for level 3 





Level 3:
Ssh and login to 3
Ls -a to see hidden files 
And then viewing all the hidden files to get password for level 4 



Level 4:
Use ls to view files 
Cd to enter into the directory 
file./* (from net ) to see which file is ascii text    —->file07
 open file by cat



Level 5:
Use password from 4 to open level 5
Inehre directory had  20 more  directories then we will use find command to find which directory has a file of size 1003 


Level 6:
Password from 5 
 We use ls —-> no change 
So we use ls -a for hidden files 
Using the find command to search for the file with specifications









Level 7: 
use the password from level 6 to get into level 7 
Cat data.txt piped with grep command to find password for level 8






Level 8:
Searched on google for the terms uniq and sort 
Uniq - u compares one line to each line and displays the unique one
Sort command sorts all the data .




Level 9:
Using string to convert binary to readable text 
Used grep for =
Got the password for level 10 












Level 10:
Took help from google on how to decode base 64-d











Level 11:


Rotating them by 13 positions 
Got password for level 12






Level 12:
I took help from google cause i couldnt do much by myself 
Used xd  to make hexdump or do reverse ….used file command to determine what sort of file it was .. used -d  or gzip to decompress 







level13:
Got password from level 12 
Ssh syntax
Learnt what public and private keys are .
By default  the private key is stored in ~/.ssh/id_rsa and the public key is stored in ~/.ssh/id_rsa.pub. Public keys and private keys are the working parts of Public-key cryptography. Together, they encrypt and decrypt data that resides or moves in a network. The public key is truly public and can be shared widely while the private key should be known only to the owner. 






Level 14:
Reading the contents of the password file then connect to the port 30000 on localhost 
Hence we got got password for level 15
Telnet command 
Telnet is an old network protocol that is used to connect to remote systems over a TCP/IP network. It connects to servers and network equipment over port 23
The two types of protocol:
Tcp and ip TCP/IP stands for Transmission Control Protocol/ Internet Protocol. It is a set of conventions or rules and methods that are used to interconnect network devices on the Internet.
IP is the part that obtains the address to which data is sent. TCP is responsible for data delivery once that IP address has been found.
A port is a number assigned to uniquely identify a connection endpoint and to direct data to a specific service.




Level 15:
Openssl - implement tls (transport layer security )
s_client
-connect (connects the socket referred to by the file )
-quiet (given in prompt)
Piping - for redirection 
To send output of one command to another command/programme 
Using cat command , piping ,openssl and then connected with localhost 






Level 16: 
Had to watch yt video for this 
Not very clear with this level 









Level17:
Using ls command to check the contents of the file 
Used diff command - diff is a command-line utility that allows you to compare two files line by line. It can also compare the contents of directories. 





Level18:
everytime we enter the password it closes the connection of this level. 
we use a cat command together with the ssh statement to get the password.



Level19:
Use ls to check the contents of the file 
Then we use the cat command along with the file name 
Etc command helps us to get the password for the next level 
The /etc (et-see) directory is where a Linux system's configuration files live. $ ls /etc. A large number of files (over 200) appear on your screen









Level20:
we need to open 2 terminals and connect it using ./filename
After the 2 terminals are connected
 we send the 1st terminal the password of that level through the 2nd terminal and if it matches, the 1st terminal sends back the new password to the 2nd terminal.




Level21:
Using ls to list all the contents of the file , then we try to check all the files using the cat command 
Password was in the cronjob_bandit22 file.






Level 22:
List the contents of the file using cat command and get the user that is logged in . we use that along bandit 23 to get empty file text .
Again use cat command to get the contents of the file 
We get the password for the next level 
 



Level 23:
Looked up from google and saw the youtube video 
Wasn't clear with this level .













