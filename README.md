# Access Termux Remotly
	
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
*	Install TailScale to another device that will be used to connect to Termux SSH and login with same account.
