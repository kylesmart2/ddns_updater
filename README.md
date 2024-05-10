# ddns_updater
This is dedicated to a C++ program that can be compiled and set as a cron job to keep your public IP up-to-date with your DDNS provider.

Prerequisites
  This application was primarily written to be compiled and executed in Linux or MacOS. There are commands in this application that will require
  your Linux install to have some DNS utilities installed to use the dig command. Debian based OS:
  ```
  sudo apt install dnsutils
  ```

Open DDNSUPDATER_DIY.cpp with your preferred text editor or IDE. 
Locate comment above defined global variable for where to enter your DDNS curl command.
Save the file and it is ready to be compiled and executed. 
I use g++ to compile my C++ code. Note, you can name it whatever you'd like. The name comes after the -o in the command so feel free to change it.
```
g++ ~/DDNSUPDATER_DIY -o ddnsupdater
```
Now you're ready to run the software. 
```
./ddnsupdater
```


