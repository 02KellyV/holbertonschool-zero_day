# Vagrant

We review topics such as:

-   Vagrant:

	- What is a zero-day?
	The term "zero day" refers to a newly discovered software vulnerability and not patched yet, it's the time since it is found until it is "fixed." If hackers manage to exploit that security hole at that time, that is known as a zero-day attack.
	
	- What is a virtual machine? What is Vagrant?
	VM is a version control box and environments, Vagrant do this, like a VirtualBox but better haha. Think about it! 
	**Vagrant** starting a Ubuntu virtual machine using **vagrant up**

	- Who wrote Vagrant?
	Original author: Mitchell Hashimoto. 
	Developers: HashiCorp (Mitchell Hashimoto and John Bender)
	- Use Vagrant:
		- Install VirtualBox: Download VirtualBox from this [link](https://intranet.hbtn.io/rltoken/Z2roTuyhhdPF0CnohrZQIw "link")
		- Install Vagrant: Download Vagrant from this [link](https://intranet.hbtn.io/rltoken/0WSgWVLsNmTFDTgwy1Xg1Q "link")
		- Open the [command prompt](https://intranet.hbtn.io/rltoken/O6EMH3CGZ2Cm2ApusfVHqg "command prompt")
		- Add the **Ubuntu 14.04 (Trusty)** image to your box list:
			- C:\dir> `vagrant box add ubuntu/trusty64`
			- C:\dir> `vagrant init ubuntu/trusty64`
			- C:\dir> `vagrant up`
			- C:\dir> `vagrant ssh`
		- Note: If doesn't works, download the img vagrant from my [drive](https://drive.google.com/open?id=1PL7lkYJn-PcN72C4rpd0kBKUSC83LbM7). 
    (Copy the dir and paste in ypur Windows pc, rute: _c:\users\pc1\.vagrant.d\boxes_)
    
    #### That is all! The party begins in Holberton!
