# Writing-Custom-Rules
This is the second part of using Snort as IDS, in this section, there will be details on how to write a custom rule for Snort.
Before writing any custom rules, you probably want to add a number in front of every line, it will be easy to read.

1. Add numbers in front of every line
<p align="center">
<img src="https://imgur.com/6KhNjXA.png" height="80%" width="80%" >
<p align="center">
<img src="https://imgur.com/azKGXIQ.png" height="80%" width="80%" >
  
2. Now numbers add to each line, let's comment the orginal rules, 
  so we can write the custome rules and test rules later.
  When you comment all the rules out, leave /etc/snort/rules/local.rules uncommented.
<p align="center">
<img src="https://imgur.com/edEUIub.png" height="80%" width="80%" >
  
3. Using the text editor to edit the local.rules file
<p align="center">
<img src="https://imgur.com/ucBS4SI.png" height="80%" width="80%" >
  
4. After open the text editor, enter the following command
<p align="center">
<img src="https://imgur.com/nqWmzFw.png" height="80%" width="80%" >

5. Let's test the custom rule just created by the following command
<p align="center">
<img src="https://imgur.com/9piWQaL.png" height="80%" width="80%" >

6. The custome rule is about "ping" a device is online or not
<p align="center">
<img src="https://imgur.com/0kcUwR0.png" height="80%" width="80%" >

7. Check the terminal if you run step 5 showing a remote IP try to ping the host
<p align="center">
<img src="https://imgur.com/frTgn81.png" height="80%" width="80%" >

8. Add another rule for SSH connection
<p align="center">
<img src="https://imgur.com/9xfGssj.png" height="80%" width="80%" >

