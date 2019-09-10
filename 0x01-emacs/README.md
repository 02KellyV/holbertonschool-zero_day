# Emacs

- Emacs:
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

