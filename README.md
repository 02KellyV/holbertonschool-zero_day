# Welcome to my first project!

Hi! In this repo i pushed my first file in my **first repository** of the **first task** of my **first Holberton School project**.

We review topics such as:
-   [Vagrant](https://github.com/02KellyV/holbertonschool-zero_day/tree/master/0x00-vagrant):
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
		> Note: If doesn't works, download the img vagrant from my [drive](https://drive.google.com/open?id=1PL7lkYJn-PcN72C4rpd0kBKUSC83LbM7). (Copy the dir and paste in ypur Windows pc, rute: _c:\users\pc\ .vagrant.d\boxes_)

- [Emacs](https://github.com/02KellyV/holbertonschool-zero_day/tree/master/0x01-emacs):
	- Who is Richard Stallman?
	**Richard** Matthew **Stallman** known by his initials: RMS, is an American free software movement activist and programmer for Emacs, GCC y GNU Debugger, etc... 
	- Install `emacs` in your terminal:
		- `sudo apt-get update`
		- `sudo apt-get upgrade`
		- `sudo apt-get install emacs`

	-  [Guided Tour for Emacs](https://www.gnu.org/software/emacs/tour/)

		|    command | stands for |
		|---------------|:------------:|
		|    C-k, C-y |  cut and paste an entire line |
		|    C-s |  search forward |
		|    C-/ |  undo |
		|    C-x C-f |  open a file from within Emacs |
		|    C-x C-s |  save a file |
		|    C-x C-c |  quit Emacs |
		|    M-x tetris |  play Tetris inside Emacs |
		|    M-x doctor |  talk to your doctor |

- [Vi](https://github.com/02KellyV/holbertonschool-zero_day/tree/master/0x02-vi)
	- What is vi? 
	**vi** is a text **editor** written by Bill Joy (co-founder Sun Microsystems) in 1976 for an early BSD oses.
	
	- Who is Bill Joy?
	**Bill Joy** is a well-known computer software engineer, businessman, and futurist. 
	- [Basic vi Commands](https://intranet.hbtn.io/rltoken/TvhnXN1GAP7Et5OSuceGqw "Basic vi Commands")
	
		|    command | stands for |
		|---------------|:------------:|
		|    vi filename |  insert text before the cursor |
		|    yy |  cut (yank) the current line |
		|    p |  paste the lines in the buffer into the text after the current line |
		|    u |  undo what you just did |
		|    :q!<Return> |  quit vi even though latest changes have not been saved for this vi call |
		|    0 |  move the cursor to the start of the current line |
		|    $ |  move the cursor to the end of the line |
		|    :(no. line) |  move the cursor to no. line  |
		|   1dk | delete the current and previous line at the same time |

- [Github](https://github.com/02KellyV/holbertonschool-zero_day/tree/master/0x03-git):
    
    -   Create/use Github account
    -   Install Git:
        -   If `git` is not already installed on your terminal: 
	        - `$ sudo apt-get update` 
	        - `$ sudo apt-get upgrade` 
	        - `$ sudo apt-get install git`
       - Basic usage
	       - Create github remote: 
		        - `$ cd /path/to/my/codebase` 
		        - `$ git init` 
		        - `$ git add .`
		        - `$ git commit -m "first commit"`
		        - `$ git remote add https://...`
		        - `$ git push origin master (required user and password)`
        - A `README.md` file at the root of the repo, containing a description of the projects. In this way:
	        - A `README.md` file, at the root of the folder of _this_ project (e.g. `0x01-emacs`), describing what this project is about
	        - And `README.md` file in the repo, describing the projects and all the links to this directories.

-   Linux:
    -   Basic commands to navigation and modify files
-   etc...    

### Hooray!
