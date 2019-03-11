1900s- Nikola Tesla proposes an idea of a "world wireless system"

1930s- Paul Otlet and Vannervar Bush conceived mechanized, searchabke stoarage systems of books and media.

1940s- Colossu- an eclectonic digital computer was built to break german codes

1940s- Alan Turning use his Bombe Machine to break german Engima  machine

1960s- MIT J.C.R Licklider popularized the idea of "intergalactic Network"

1960s- The U.S goverment separates Military research from the military and create ARPANET or the Advanced Research Projects Agency Network

1960s- ARPANET was created as the US GOvernment neededa speedy and efficient way too commmunicate accross the country.

1960s- ARPANET uses packet switching to allow multiple computers to communicate on a single network

1960s- The first data transfer demonstrating a four-way connected network took place from Stanford University, the University of California at Santa Barbara, UCLA, and the University of Utah.

1970s- Transmission Control Protocol and Internet Protocol (TCP/IP) was created to set a standard for how data could be transmitted between mltiple networks.

1970s- Email is invented by Ray Tomlinson 

1980s- Various researchers in many universities continue to research computer connections, and the technology become more known to the public

1980s- ARPANET begin the assembly of networks which lead to the modern day internet

1990- Tim Berners-Lee invents the WOrld WIde Web, allowing people to access websites and hyperlinks

1990s- Netscape develops the first graphical browser that ran on popular computers

1990s- Internet begins to be sold to the public

1990s- The first iteration of the Internet available for commercial use was dial-up. It needed phone lines so phones could not be used while on thr internet

1990s- The first internets were very slow and expensive

2000s- Mobile phones become much more popular

2000s- Apple introduces the first "smart" phone with a touch screen and better internet connectivity

2000s- Many tech companies were overvalued based on the promise of more users. Stocks of tech companies crashed and many companies went out of bussiness

2000s- Broadband starts to replace dial up. Broadband were much faster and did not need to be pluged in to work

2010s- Fibre optic broadband becomes availiable with even higher speeds.

2010s- Internet of Things, refers to everyday items connecting to the internet.






JlCSC inter in which WebStorm lets you verify your JavaScript code.

**.travis.yml:**
this file makes use of continuous Integration, which is the practice of merging in small code changes frequently -
rather than merging in a large change at the end of a development cycle. The goal is to build healthier software by
developing and testing in smaller increments. This is where Travis CI comes in.

**CHANGELOG.MD:**
All notable changes to this project are documented in this file,such as bug fixes, new features, etc.

**gulpfile.babel.js:**
Gulp is a tool that helps you out with several tasks when it comes to web development. It's often used to do front end 
tasks like: Spinning up a web server; reloading the browser automatically whenever a file is saved; Optimizing assets 
like CSS, JavaScript, and images. Babel is a transpiler for JavaScript that has the ability to turn ES6 or ES7 into 
code that can run on your browsers and devices.

**LICENSE.txt:**                      
Text file which converys the terms under which the repository is distributed.

**modernizr-config.json:**
Modernizr is a useful JavaScript library to detect user browser capabilities on websites. Command Line Config helps to
automate the process, backed up by a Modernizr NPM module. 

**package.json:**
This file can contain a lot of meta-data about the project. But mostly it will be used for two things:
Managing dependencies of the projectScripts ; Scripts, that helps in generating builds, running tests and other stuff
in regards to the project.

**README.MD:** A README file contains information about other files in a directory or archive of computer software. 
A form of documentation, it is usually a simple plain text file.


#BEGINNER TUTORIAL ON USING GIT TO COLLABORATE EFFECTIVELY



**GIT**: Git is a free and open source distributed code management and version control system that is distributed under
the GNU General Public License version 2. In addition to software version control, Git is used for other applications 
including configuration management and content management.
Linus Torvalds, the creator of Linux, developed and released Git in 2005. The project was originally undertaken because
available open source version control systems at that time weren't up to up to the requirements of Linux kernel 
development. For one thing, version control for such a large-scale collaborative effort requires better performance than
available systems were capable of -- three seconds to apply a patch, for example, versus 30. In addition to its 
superior performance, Git provides support for a distributed workflow and safeguards against corruption. 
 
 <a href="https://s134.photobucket.com/user/carla12cool/media/octocat.jpeg.html" target="_blank"><img src="https://i134.photobucket.com/albums/q99/carla12cool/octocat.jpeg" border="0" alt=" photo octocat.jpeg"/></a>
_**Here are some definitions for clarification on the meaning of Git above if you are not familiar with some of the terms:**_

**Control System**: This basically means that Git is a content tracker. So Git can be used to store content — it is mostly used 
to store code due to the other features it provides.

**Version Control System**: The code which is stored in Git keeps changing as more code is added. Also, many developers can
add code in parallel. So Version Control System helps in handling this by maintaining a history of what changes have 
happened. Also, Git provides features like branches and merges, which I will be covering later.

**Distributed Version Control System**: Git has a remote repository which is stored in a server and a local repository which
is stored in the computer of each developer. This means that the code is not just stored in a central server, but the full 
copy of the code is present in all the developers’ computers. Git is a Distributed Version Control System since the code is 
present in every developer’s computer. 

###### **Download git**

This link has details on how to install Git in multiple operating systems:
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git


So, what makes GitHub so special? Git is a command-line tool, but the center around which all things involving Git
revolve is the hub www.GitHub.com where developers store their projects and network with like minded people.
(YOU MUST CREATE AN ACCOUNT WITH GITHUB WITH YOUR EMAIL AND A PASSWORD)

Let's explore some of the terminology in Github in order to grasp a clearer picture of the Hub.

**Repository**: A repository is  location where all the files for a particular project are stored. Each project has its 
own repo, and you can access it with a unique URL.
(AFTER YOU HAVE CREATED YOUR ACCOUNT YOU WILL BE ABLE TO CREATE AND ACCESS REPOSITORIES)
AT THE RIGHT TOP CORNER OF THE WEB PAGE YOU WILL SEE AN ADDITION SIGN DISPLAYED "+", CLICK ON IT TO ADD A REPOSITORY. 

<a href="https://s134.photobucket.com/user/carla12cool/media/Screenshot%203.png.html" target="_blank"><img src="https://i134.photobucket.com/albums/q99/carla12cool/Screenshot%203.png" border="0" alt=" photo Screenshot 3.png"/></a> 
<a href="https://s134.photobucket.com/user/carla12cool/media/repo-main-page.png.html" target="_blank"><img src="https://i134.photobucket.com/albums/q99/carla12cool/repo-main-page.png" border="0" alt=" photo repo-main-page.png"/></a>

**Clone**: The "clone" command downloads an existing Git repository to your local computer.
You will then have a full-blown, local version of that Git repo and can start working on the project. That remote 
repository's URL is then later referred to as the "origin".
(ONCE YOU ARE IN A REPOSITORY YOU WILL SEE THE GREEN CLONE/DOWNLOAD BUTTON)
<a href="https://s134.photobucket.com/user/carla12cool/media/Screenshot%204_1.png.html" target="_blank"><img src="https://i134.photobucket.com/albums/q99/carla12cool/Screenshot%204_1.png" border="0" alt=" photo Screenshot 4_1.png"/></a>
<a href="https://s134.photobucket.com/user/carla12cool/media/Screenshot%205_1.png.html" target="_blank"><img src="https://i134.photobucket.com/albums/q99/carla12cool/Screenshot%205_1.png" border="0" alt=" photo Screenshot 5_1.png"/></a>

**Commit**: A commit, or "revision", is an individual change to a file (or set of files). It's like when you save a file,
except with Git, every time you save it creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record
of what changes were made when and by who. Commits usually contain a commit message which is a brief description of what changes were made.
(COMMITS NEED TO BE MADE IN ORDER TO PUSH OR PULL, ALWAYS COMMIT AFTER YOU MAKE ANY CHANGES!)

<a href="https://s134.photobucket.com/user/carla12cool/media/Screenshot%206.png.html" target="_blank"><img src="https://i134.photobucket.com/albums/q99/carla12cool/Screenshot%206.png" border="0" alt=" photo Screenshot 6.png"/></a>

-

<a href="http://s134.photobucket.com/user/carla12cool/media/Screenshot%207.png.html" target="_blank"><img src="http://i134.photobucket.com/albums/q99/carla12cool/Screenshot%207.png" border="0" alt=" photo Screenshot 7.png"/></a>


**Push**: Pushing refers to sending your committed changes to a remote repository, such as a repository hosted on GitHub.
For instance, if you change something locally, you'd want to then push those changes so that others may access them.

<a href="https://s134.photobucket.com/user/carla12cool/media/Screenshot%208.png.html" target="_blank"><img src="https://i134.photobucket.com/albums/q99/carla12cool/Screenshot%208.png" border="0" alt=" photo Screenshot 8.png"/></a>
<a href="http://s134.photobucket.com/user/carla12cool/media/Screenshot%209.png.html" target="_blank"><img src="http://i134.photobucket.com/albums/q99/carla12cool/Screenshot%209.png" border="0" alt=" photo Screenshot 9.png"/></a>
