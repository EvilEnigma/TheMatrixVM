# TheMatrixVM
An intentionally designed vulnerable machine 'boot2root' challenge for beginners.  


### Setup ###

You will need Virtual Box or VMWare Player to import the OVA file included in this repository. I have tested this using Windows 10 and VirtualBox version 7. 

1. Set the network adapter to host-only or bridge mode, so that you can launch the virtual machine.

![image](https://github.com/EvilEnigma/TheMatrixVM/assets/23328902/54b0c6af-b7b1-4acd-9cc2-9134ac05c96c)
   
2. Monitor the console for messages if all goes well you should spot the VM receiving an IP address.
   
![image](https://github.com/EvilEnigma/TheMatrixVM/assets/23328902/1e056531-5bab-47cd-b457-b66263159bbb)

3. Attempt to SSH to the machine ssh test@<ip.seen.from.console>

4. If you get a prompt of SSH keys being accepted, you are in a good shape to continue.

5. Perform an NMAP scan like how Trinity did to hack the grid! try all ports :) 

6. Good luck and enjoy the CTF! 

## Learning Pre-Requisites ##

- This VM does not require exploiting a CVE, or use of MetaSploit/Commercial exploit tools.
- Requires intermediary knowlege of linux as it is based on Alpine.


