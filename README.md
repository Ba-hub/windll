# windll
## Made By : Ghosthub

Malicious DLL generator for DLL Hijacking & Connection Setup On CMD

### About dll Files :
```



Stands for "Dynamic Link Library." A DLL (.dll) file contains a library of functions and other information that can be accessed by a Windows program. When a program is launched, links to the necessary .dll files are created. If a static link is created, the .dll files will be in use as long as the program is active. If a dynamic link is created, the .dll files will only be used when needed. Dynamic links help programs use resources, such as memory and hard drive space, more efficiently.

DLL files can also be used by more than one program. In fact, they can even be used by multiple programs at the same time. Some DLLs come with the Windows operating system while others are added when new programs are installed. You typically don't want to open a .dll file directly, since the program that uses it will automatically load it if needed. Though DLL filenames usally end in ".dll," they can also end in .exe, .drv, and .fon, just to make things more confusing.



```

### Features:
#### Custom Port Forwarding option (LHOST,LPORT)
#### Example of DLL Hijacking included (Half-Life Launcher file)
#### Connection Received By Netcat


### Requirements:
#### Mingw-w64 compiler: apt-get install mingw-w64
#### Ngrok Authtoken (for TCP Tunneling): Sign up at: https://ngrok.com/signup
#### Your authtoken is available on your dashboard: https://dashboard.ngrok.com
#### Install your auhtoken: ./ngrok authtoken <YOUR_AUTHTOKEN>
### ** You Can Forward Port By Portmap.io, sshreachme.com Or Any Other Service. 


### Usage:
```
git clone https://github.com/Ba-hub/windll.git
cd windll
bash windll.sh
```
