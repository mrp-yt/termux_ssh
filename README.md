# Access Termux Remotely
	
## Setup remote SSH connection to Termux from anywhere using TailScale
	
*	Install Tailscale on your android device

*	Install openssh in Termux
	```
	pkg isntall openssh -y
	```
*	Create password for SSH connection
	```
	passwd
	```
*	Start SSH service by executing
	```
	sshd
	```
*	Install TailScale to another device that will be used to connect to Termux SSH and login with same account.

*	Use your prefered SSH client and connect to Termux SSH. Use TailScale assigned IP address for connection and port number `8022`
