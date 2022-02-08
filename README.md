# VSFTPD v2.3.4 vulnerabilities
Backdoor Command Execution VSFTPD v2.3.4.

From the vulnerability assessment we’ve learned that this version of VSFTPD might contain a backdoor which has been created by an intruder. Although the backdoor was identified and removed quickly by the developers, many people have downloaded and installed the backdoored version of VSFTPD. The backdoor payload is initiated in response to a :) character combination in the username which represents a smiley face. The code sets up a bind shell listener on port 6200.

##

References:

OSVDB (73573)

http://pastebin.com/AetT9sS5

http://scarybeastsecurity.blogspot.com/2011/07/alert-vsftpd-download-backdoored.html

https://www.hackingtutorials.org/metasploit-tutorials/exploiting-vsftpd-metasploitable/

##

### 📋 Requirements

To run it is necessary to use a linux terminal and install the following utilities:

```
apt-get install python
```
```
apt-get install netcat-traditional
```
