# FTP_basics
This repo is to learn basics of ftp using command line


## Steps to access ftp(for android using CX-file explorer)
1. Start host service and make sure pc and mobiles are on same network or pc is connected to mobile hotspot.
2. Comfigure your firewall using 
   ```
   firewall-cmd --permanent --add-port=21/tcp
   firewall-cmd --permanent --add-service=ftp
   firewall-cmd --reload
   ```
3. On pc terminal type ``` ftp x.x.x.x yyyy ``` ( for ftp://192.168.1.77:6466 command will be ``` ftp 192.168.1.77 6466 ```) **Remember that chracters after semicolon ':' are typed after adding space.**
4. Configure using username and password.
5. List of all commands can be seen here https://phoenixnap.com/kb/linux-ftp
   Syntax ``` ftp [options] [IP] ```
6. Now we can manipulate with remote device's files using operations like copy,cut,paste,rename etc.


## FTP's alternate can telnet which is also an application layer and is more secure, basics can be found here
1. Start host service and make sure pc and mobiles are on same network or pc is connected to mobile hotspot.
2. Comfigure your firewall using 
   ```
   firewall-cmd --permanent --add-port=21/tcp
   firewall-cmd --permanent --add-service=ftp
   firewall-cmd --reload
   ```
3. On pc terminal type ``` telnet x.x.x.x yyyy ``` ( for ftp://192.168.1.77:6466 command will be ``` telnet 192.168.1.77 6466 ```) **Remember that chracters after semicolon ':' are typed after adding space.**
4. Configure using username and password.
5. List of all commands can be seen here https://www.computerhope.com/unix/utelnet.htm
   Syntax ``` ftp [options] [IP] ```
6. Now we can manipulate with remote device's files using operations like copy,cut,paste,rename etc.

   
