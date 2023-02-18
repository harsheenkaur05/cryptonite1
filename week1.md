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


<img width="245" alt="image15" src="https://user-images.githubusercontent.com/120416962/217062823-c7d69eed-6932-4b08-ae2b-28c932c5a27f.png">






USING SSH command to log in and use ls to see what is there in the directory 
Opening readme using cat  to see what is there inside the file 
 We got the password for level 1 from level 0 
Level 1:


<img width="285" alt="image14" src="https://user-images.githubusercontent.com/120416962/217063050-f3cde96c-2e50-4775-a515-a39a6545aa1f.png">




We use ls to see what's in the directory 
Cat - doesnt work 
ctr+d to get out 
Password from level 1 to go to level 2 

 Level 2:
Ls -a  to view all files 
Using cat command opened “spaces in this filename ”
We get password for level 3 


<img width="455" alt="image31" src="https://user-images.githubusercontent.com/120416962/217063104-e1258501-f8bb-4fc4-91f9-175d65dbdd7d.png">




Level 3:
Ssh and login to 3
Ls -a to see hidden files 
And then viewing all the hidden files to get password for level 4 


<img width="366" alt="image1" src="https://user-images.githubusercontent.com/120416962/217063190-46f55d36-c0f9-424d-951c-abc99f2dbe67.png">






Level 4:
Use ls to view files 
Cd to enter into the directory 
file./* (from net ) to see which file is ascii text    —->file07
 open file by cat


<img width="336" alt="image7" src="https://user-images.githubusercontent.com/120416962/217063237-2bd14460-8020-491f-a482-be0309882aec.png">




Level 5:
Use password from 4 to open level 5
Inehre directory had  20 more  directories then we will use find command to find which directory has a file of size 1003 



<img width="515" alt="image5" src="https://user-images.githubusercontent.com/120416962/217063313-ee35dd1a-cd27-47a2-b87f-057c013bffe5.png">





Level 6:
Password from 5 
 We use ls —-> no change 
So we use ls -a for hidden files 
Using the find command to search for the file with specifications



<img width="791" alt="image26" src="https://user-images.githubusercontent.com/120416962/217063378-e799532d-78c6-49fc-bd1c-63e943baf277.png">





Level 7: 
use the password from level 6 to get into level 7 
Cat data.txt piped with grep command to find password for level 8


<img width="406" alt="image9" src="https://user-images.githubusercontent.com/120416962/217063471-81d5b687-6a87-4d0b-ab08-6fde7e9d663e.png">





Level 8:
Searched on google for the terms uniq and sort 
Uniq - u compares one line to each line and displays the unique one
Sort command sorts all the data .


<img width="324" alt="image22" src="https://user-images.githubusercontent.com/120416962/217063936-87dbf9fb-9a1b-426b-a8ea-7e7a5c9b75e1.png">


Level 9:
Using string to convert binary to readable text 
Used grep for =
Got the password for level 10 



<img width="406" alt="image25" src="https://user-images.githubusercontent.com/120416962/217064049-bafd84e1-5af5-496c-9990-937fd040356e.png">






Level 10:
Took help from google on how to decode base 64-d




<img width="530" alt="image20" src="https://user-images.githubusercontent.com/120416962/217064143-9b01007b-8e86-4dd0-86fa-50ceabc7a5bb.png">






Level 11:


Rotating them by 13 positions 
Got password for level 12


<img width="486" alt="image3" src="https://user-images.githubusercontent.com/120416962/217064235-a24339a5-c93d-4e04-a05e-d6d47ed2a49f.png">



Level 12:
I took help from google cause i couldnt do much by myself 
Used xd  to make hexdump or do reverse ….used file command to determine what sort of file it was .. used -d  or gzip to decompress 



<img width="868" alt="image6" src="https://user-images.githubusercontent.com/120416962/217064313-e6fa0a24-27e6-4ed9-9932-0738ad21b884.png">



![image4](https://user-images.githubusercontent.com/120416962/217064358-88d0e134-e285-4119-a7ce-baf9bfaf626f.png)



level13:
Got password from level 12 
Ssh syntax
Learnt what public and private keys are .
By default  the private key is stored in ~/.ssh/id_rsa and the public key is stored in ~/.ssh/id_rsa.pub. Public keys and private keys are the working parts of Public-key cryptography. Together, they encrypt and decrypt data that resides or moves in a network. The public key is truly public and can be shared widely while the private key should be known only to the owner. 


<img width="608" alt="image28" src="https://user-images.githubusercontent.com/120416962/217064568-807e20bd-7100-417f-a259-9bfc9f64c4be.png">



Level 14:
Reading the contents of the password file then connect to the port 30000 on localhost 
Hence we got got password for level 15
Telnet command 
Telnet is an old network protocol that is used to connect to remote systems over a TCP/IP network. It connects to servers and network equipment over port 23
The two types of protocol:
Tcp and ip TCP/IP stands for Transmission Control Protocol/ Internet Protocol. It is a set of conventions or rules and methods that are used to interconnect network devices on the Internet.
IP is the part that obtains the address to which data is sent. TCP is responsible for data delivery once that IP address has been found.
A port is a number assigned to uniquely identify a connection endpoint and to direct data to a specific service.



<img width="560" alt="image30" src="https://user-images.githubusercontent.com/120416962/217064623-45c14c74-427e-401e-a52f-7dcca92e94d0.png">







Level 15:
Openssl - implement tls (transport layer security )
s_client
-connect (connects the socket referred to by the file )
-quiet (given in prompt)
Piping - for redirection 
To send output of one command to another command/programme 
Using cat command , piping ,openssl and then connected with localhost 


<img width="636" alt="image17" src="https://user-images.githubusercontent.com/120416962/217064754-00ec3afe-fc54-4233-a0e5-a6ce1169de49.png">



Level 16: 
Had to watch yt video for this 
Not very clear with this level 


![image11](https://user-images.githubusercontent.com/120416962/217064812-a59bb5c7-482c-45d1-b3d6-af8cd80d048f.png)



![image27](https://user-images.githubusercontent.com/120416962/217064851-77996584-ea1c-4b39-a58f-f656f90d2ce3.png)


![image8](https://user-images.githubusercontent.com/120416962/217064929-e126a537-a8e1-4f3b-9f92-670f9e491aef.png)



Level17:
Using ls command to check the contents of the file 
Used diff command - diff is a command-line utility that allows you to compare two files line by line. It can also compare the contents of directories. 



![image13](https://user-images.githubusercontent.com/120416962/217065001-1ff78a8b-0374-4873-9b2a-9efc29b16abd.png)



Level18:
everytime we enter the password it closes the connection of this level. 
we use a cat command together with the ssh statement to get the password.




![image10](https://user-images.githubusercontent.com/120416962/217065070-794869c2-8d80-45ec-a6ca-59dd12718dce.png)



Level19:
Use ls to check the contents of the file 
Then we use the cat command along with the file name 
Etc command helps us to get the password for the next level 
The /etc (et-see) directory is where a Linux system's configuration files live. $ ls /etc. A large number of files (over 200) appear on your screen


![image12](https://user-images.githubusercontent.com/120416962/217065143-d6e420e9-2043-4f6e-bb65-f972c397866a.png)






Level20:
we need to open 2 terminals and connect it using ./filename
After the 2 terminals are connected
 we send the 1st terminal the password of that level through the 2nd terminal and if it matches, the 1st terminal sends back the new password to the 2nd terminal.



![image24](https://user-images.githubusercontent.com/120416962/217065768-88a51062-bb7e-4e93-8d49-302941f2b417.png)





Level21:
Using ls to list all the contents of the file , then we try to check all the files using the cat command 
Password was in the cronjob_bandit22 file.


![image29](https://user-images.githubusercontent.com/120416962/217065842-ce391a1c-2266-4831-9e52-9d98741df6d5.png)



Level 22:
List the contents of the file using cat command and get the user that is logged in . we use that along bandit 23 to get empty file text .
Again use cat command to get the contents of the file 
We get the password for the next level 
 

![image16](https://user-images.githubusercontent.com/120416962/217065926-7b907d9c-7849-4f98-903e-74f587a88010.png)





![image21](https://user-images.githubusercontent.com/120416962/217066017-ee1c6c79-56df-4f28-b3e8-16e504e1d2bf.png)



Level 23:
Looked up from google and saw the youtube video 
Wasn't clear with this level .



![image18](https://user-images.githubusercontent.com/120416962/217066102-da01ec87-4056-4ca4-a995-aac016be64f1.png)










