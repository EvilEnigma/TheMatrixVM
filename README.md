# TheMatrixVM
An intentionally designed vulnerable machine 'boot2root' challenge for beginners.  


### Setup ###

You will need Virtual Box or VMWare Player to import the OVA file included in this repository. I have tested this using Windows 10 and VirtualBox version 7.  

1. Download the Virtual Machine from Release tab - https://github.com/EvilEnigma/TheMatrixVM/releases/download/first/TheMatrix.zip

2. Set the network adapter to host-only or bridge mode, so that you can launch the virtual machine.
![image](https://github.com/EvilEnigma/TheMatrixVM/assets/23328902/71eb7b6f-e10d-4cc9-9ba9-4291be3bc427)


3. Monitor the console for messages if all goes well you should spot the VM receiving an IP address.

![image](https://github.com/EvilEnigma/TheMatrixVM/assets/23328902/2fbcd531-9bab-4daf-8b28-3b5b85fc2bfc)

4. Attempt to SSH to the machine ssh test@<ip.seen.from.console>

5. If you get a prompt of SSH keys being accepted, you are in a good shape to continue.

6. Perform an NMAP scan like how Trinity did to hack the grid! try all ports :)

Good luck and enjoy the CTF! There are plenty of flags along the right path.

## Learning Pre-Requisites ##

- This VM does not require exploiting a CVE, or use of MetaSploit/Commercial exploit tools.
- Requires intermediary knowlege of linux as it is based on Alpine.


