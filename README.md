# RATS
**user must have sudo rights**  
Remote Access Tool Service  
Make a persistent service with a custom script by using systemd on the fly  

The goal of RATS, in this case, is leave a nc connection always listening as a permanent systemd service.  
The resultant is a root shell  

# Screenshots 

Run **sudo** bash RAT-service.sh  
![alt text](https://github.com/0bfxGH0ST/RATS/blob/main/screenshots/screenshot01.png)  
![alt text](https://github.com/0bfxGH0ST/RATS/blob/main/screenshots/screenshot02.png)  
Connecting to the permanent service via netcat and...BOOM! Root privileges after connect  
![alt text](https://github.com/0bfxGH0ST/RATS/blob/main/screenshots/screenshot03.png)  
