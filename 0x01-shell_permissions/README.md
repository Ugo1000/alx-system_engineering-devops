Permissions
Every File in in the linux / Mac Os Operating System Has 3 permisssion  :
REad , Write . Execute .

The first letter indicate the type of file 
- means it regular / normal file 
d - means it's a directory 
l - means it's its's link 

chmod can be use din two ways  symbolic argument and numbric al arguments 

a - stands for all 
u - standsfor user
g - stands for group
o- stands f or others


example :
chmod a+r filename
chmod a +rw file name 
chmod o-rwx filname 

In case you are editing a folder you can apply the permission to every 
file contained in theat folder using -r (recursive) flag

Numerical argument are fast but i find them hard to rembember 

1 if has execution permission 
2 if has write permission
4 if has read permission


This gives us four combinations: 

0 no permiision
1 can execute 
2 can write 
3 can write , execute 
4 can read 
5 can read , excute 
6 can read , write 
7 can read , wite , execute 
