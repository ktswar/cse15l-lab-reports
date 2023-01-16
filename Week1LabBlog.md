# CSE 15L - Week 1 Lab Report
### Name: Mary Swar
### Lab: Wednesday, 11 am in Room B260
---

This is how I went through the process of installing Visual Studio Code and remotely connecting to the server.
1. **First, I downloaded Visual Studio Code program by going [HERE](https://code.visualstudio.com/)**
   
   It was very straightforward- I just clicked the button circled in red and followed all of the suggested installation steps:
   ![VS Download](https://lh6.googleusercontent.com/GhZcXHwBR27SpWJJysNOG44PDDRxCAQUBDfCvoL-2VAOJqXPl2DXtopQpY5F85ET5DE=w2400)
   
2. **Then, since I'm running on Windows, I installed Git [HERE](https://gitforwindows.org/)**

   Same as above, I just clicked the download button and followed all of the installation instructions:
   ![Git for Windows](https://lh5.googleusercontent.com/5ezi22X2KdYiWkGtEWcNIkp7I0-pQ0gIFeJ-pCapMm_mijGs0gzkXjHsdkuNI2CiXXM=w2400)
   
3. **I then had to enable the Git Bash terminal in Visual Studio. I went to this website to learn how: [Stack Overflow Instructions](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal/50527994#50527994)**

   This is what it said to do:
   ![GitBash Instructions](https://lh5.googleusercontent.com/3_s3DucybV8aYr_hzQPoJjn8SJE8eeghncSBUxjddFaauZKF7BEMpxGrBe1jzDAvvGQ=w2400)
   
4. **Once I had everything I needed installed and enabled, I had to go [HERE](https://sdacs.ucsd.edu/~icc/index.php) to look up my what ETS username was assigned to me. This is the username I would be using to log in to the system (not my student ID or UC username). I filled in my information and it brought me to this screen:**
   ![user name](https://lh5.googleusercontent.com/KIzyXvWuug0r2GWxco5CbWYLZvfG2I-bVzHK3Nbl-yTi3F7A4i2P9ZMffisPdFHCSDk=w2400)
   **Below where it says 'Additional Accounts' there is a button labeled with what my assigned ETS username is. When I clicked on that button it brought me to another page to set up a password to specifically use when I remotely log in to the system. I set that and waited about 30 minutes for it to reset.**
   
5. **To log in, I opened up the terminal in VS Studio by pressing Ctrl + `. Then I type in my ETS username followed by '@ieng6.uscd.edu': 
```
ssh cs15lwe23aaz@ieng6.ucsd.edu
```
**It prompted me for my password, and when I typed it in, I didn't see any characters appearing on the screen, so if I made a mistake typing I had to backspace more than probably necessary and retype it in.**

**The screen read a welcome message saying:**
```
Hello cs15lwe23aaz, you are currently logged into ieng6-201.ucsd.edu

You are using 0% CPU on this system
```
**It displays how many users are logged in to each server and then displayed a command prompt where I could try commands to see what results I get. Here is what I got:
![results](https://lh5.googleusercontent.com/d2v7AtDRdCYhEK2Fin6Vx1zBR4v3X5x0yA__i2OS6DTZgDgxTUNGFXiUIg7kkmCRG5E=w2400)
