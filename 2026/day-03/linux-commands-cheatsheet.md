day 3
 Today i am going to learn about linux 20 commands with the help of the tutourials
cheat sheet code 
SSH ,Pa
cakge installer, USER management , File management , volume management Grep,aws,find,SED
 The 10 video of the Linux i am learning 
  **SSH means **
  key based authentication 9 when you do key based authentication, we use the SSH
  if you using the putty then use the PPK file
  allow the ssh in when creating the instant in AWS in azure its (VM) and then connect the SSH client 
  SSH is a protocol(where set of rules that need to be followed) it works on secure shellFirst letter of secure and sh from sh means the SSH 
  why we are using this because of credentials SSH works on both keys one is private keys and the other one is public key
  if i server a wants to connect with server b then sever should have private key and the sever b should have public key

  pacakge installer
ubuntu will be apt, redhat will be rpm,dnf,cnetos will be yum so now we have ubuntu
man apt
apt intall you will install pacakges,update say u will download karsatkhey, if you need to reac manual then follow man apt
i want to install the nginx page (webs erver) docker as (container) ( if i want to kow where exatly then enter the whoami
your not allowed to install the pakcages in the root, super user do sudo apt install nginx , docker.io
if update if docker images not dowload 9 update means download upgrade mean install 

systemctl status nginx  will give status of nginx 
if you enter directl systemctl stop from same then its not going to work then if you do sudo stop nginx then it going to stop
journalctl,units
now we are going to learn about the user management 
sudo is admin and rest of ar users then how we need to manage the , 
to add user then we use useradd userdel then del if i dont know the commands for users then we use man passwd u can add user or edit user name  y
useradd useradd -m berlin if you want ot add directory in home directory then you need to use sudo useradd -m berlin
in home directory thepassword it atoumaticALLY CREATES THE user name if you wanna add password then use the pssws berlin (foldername) if its not going to work use sudo passwd be
if password is clearted i want to switch from one home to other home the enter the su (Switch suser) bernlin
after entering the password it  you will see the Dolalr symbol, how you will come to know the user then search wjoami
when you want to create the file with user name then enter useradd -m tokiyo -s /usr/bin/bash -p test@123 

however when you enter the ls it will not ask for password because the password should be encrypted its writte in the folder of man doc
now if you want to exit from it then enter exit and enter it you will be switched to root user,now we want to add group then sudo -m groupadd devops  then enter want to see by entering the cat /etc/group
if i want to give permission to the group then we need to enter the  sudo gpass -a tokio devops
if u wanna switch users then enter us name, we can also modify the user too 
gpasswd.groupadd.us
sudo usermod -aG docker ubuntu , i want to each and everytime
TO be continued......

02/11/2026

I want to change the owner ship then  then we use the Chown to tokyo to josh  if not going to work then use sudo  (man chown)
owner got changed however the group is not going to change then we learned about the user management .

file management (how your going to manage)
read (cat)r
Write (Vim/nano)w
Execute (shell.executable file ./)x
i created the file and edited it and read and write, 
drwxrwxr-x pair the this from back side 
-rw-rw-r-- (- means file ,d means directory) first will say about owner secound will be group and last will be the other users
i want to give the ownership for the  we need to give permssion to the file then we have to use true  r will have 4 0 and 4 1 w 2 0 then 2 1 and x will be 01010101
if want ot give permission then we use 664 ,400 all 777 it measn giveing the permission to users (start creating,reading,deelting,modifying file)
we will be doing the 

QA

passes output of one command as input to another pipe operator uses
etc/shadow password will save the encrypted password
df -h humanreadable format
identify the cpu utilization first step 
ssh key based authentication is most secure way to conenct the linux
useradd is to add new user 
file ownership is most to check the even though he has permission
chgrp is commnad both owner and grup is changed 
apt s ubuntu package 
lsblk command is used to list all block devices attahced to linu system
check block devices using lsblk a new sik is attached to an EX2 instance but not visible what should you fo first
permanently mount a volume across reboots we use ec/fstab
ssh-keygen is right key 
usermod -ag group user is adding existing user


