
# How to set up filezilla server and client

We are setting up a filezilla server and client for the purpose of checking the user experience of
using the FTP protocol before coding the program.

How to set up ftp server:
https://macarthur.me/posts/quick-dirty-ftp-server-digital-ocean

Info on troubleshooting: 
https://www.tecmint.com/install-proftpd-in-ubuntu-and-debian/

- Note: In order to get <username> loggin in, needed to create the /home/<username> directory for the particular user. 

FTP client choices: 
1. Ancient - ftp ()
2. ncftp (https://www.ncftp.com/ncftp/)
3. lftp (http://lftp.yar.ru/)

Using ftp: 
- In order to use `ls` with the `ftp` client, had to start in passive mode: ftp -nvp. -n prevents it from auto-logging in such that we can use our custom user and password. 
    - i.e. `user si74`, then enter password. 

TODO: 
1. Figure out how to login directly to /home/ftptest. How can a user login without a home/username directory?
Dig through this config: 
https://unix.stackexchange.com/questions/83221/how-to-create-a-ftp-user-with-specific-dir-access-only-on-a-centos-linux-ins

