# The document on docsify

![](https://lh7-us.googleusercontent.com/D_eaC78Ov4siaZ5NjspxI4eyL95cBd0zuM9kX1-ZUzRq6Irx2Br0JxYLJUJ-ZGKs4cYqEvoVGq-pSdMfsVSAH0nQ_GoVpomQVw8V2b8_7ExOMXRiHvs0hKYGWuofAooH_HOO1Epdut31Gy34jVxN4I5XbCWCRneArXBDCthWZZ83xH_dlw6wjg83qx1s1w)                                                                                                           


 












Rohit Kumar
Intern
Keen & Able Computers Pvt. Ltd.

docsify	
What it is	
Get started with Docsify	
Features	


# TABLE OF CONTENT 

[1.What is Docsify ? ](https://github.com/rohit1910kmr/docsify_rk#docsify)
[2.Some key features of Docsify included] (https://github.com/rohit1910kmr/docsify_rk#some-key-features-of-docsify-include)

[3. Features of docsify]

[4. Advantages and Disadvantages of Docsify ]
[5. Step by step guide to installation and Setup](


























# docsify
A magical documentation site generator.
Docsify is a lightweight, flexible, and easy-to-use documentation generator that helps you create beautiful documentation websites using Markdown files. It's designed to be simple to set up and use, making it a popular choice for developers and teams looking to publish documentation quickly and efficiently.

With Docsify, you write your documentation content in Markdown format, and Docsify converts it into a dynamic, single-page application (SPA) website. This means users can navigate your documentation seamlessly without having to wait for page reloads.

# Some key features of Docsify include:

1. *Markdown Support*: Write documentation using Markdown syntax, making it easy to format text, add links, images, code blocks, and more.

2. *Single Page Application (SPA)*: Docsify generates a SPA website, allowing users to navigate documentation smoothly without page reloads.

3. *Customization*: Customize the appearance and behavior of your documentation website using themes, plugins, and configuration options.

4. *Auto-generated Table of Contents*: Docsify automatically generates a table of contents based on your Markdown files, making it easy for users to navigate large documents.




5. *GitHub Integration*: Docsify works seamlessly with GitHub Pages, allowing you to host your documentation directly from a GitHub repository.

Overall, Docsify provides a straightforward and efficient way to create and maintain documentation websites, making it a popular choice for developers and projects of all sizes.


# What it is
Docsify generates your documentation website on the fly. Unlike GitBook, it does not generate static html files. Instead, it smartly loads and parses your Markdown files and displays them as a website. To start using it, all you need to do is create an index.html and deploy it on GitHub Pages.
To help you solve this problem, I'd recommend a tool called docsify. Docsify is a simple and lightweight documentation generator. You can start using it without having any knowledge of JavaScript or React.
Docsify comes with zero configuration, no statically built HTML files, multiple theme support, inbuilt plugin API, and full-text search support with a plugin. It also deploys on a wide range of platforms like GitHub pages, GitLab Pages, Firebase Netlify, Vercel, and others.
I created a demo project to show you how to use it – the source code is available on GitHub. You can also check out the live demo site.

# Features

No statically built HTML files
Simple and lightweight
Smart full-text search plugin
Multiple themes
Useful plugin API
Emoji support






# Get started with Docsify

Setting up Docsify in Ubuntu involves a few simple steps:

Install Node.js and npm: Docsify requires Node.js and npm to run. You can install them using the following commands:

sudo apt update
sudo apt install nodejs npm

Install Docsify CLI: Once Node.js and npm are installed, you can install the Docsify CLI globally using npm:

sudo npm install -g docsify-cli
Create a Documentation Directory: Create a directory where you want to store your documentation files. For example:
mkdir my-docs
Initialize Docsify: Navigate into the directory you just created and initialize Docsify:
cd my-docs
docsify init .
Start Docsify Server: Start the Docsify development server by running the following command inside your documentation directory:
docsify serve
Access Documentation: Once the server is running, you can access your documentation by opening a web browser and navigating to 
http://localhost:3000.

# Steps By Steps Guide

Step 1: Install Node.js and npm

- Open a terminal on your Ubuntu system.

* Update the package list to make sure you have the latest

```
sudo apt update
```
sudo: This is a command that stands for "superuser do." It is used to execute commands with elevated or administrative privileges.

apt: Stands for "Advanced Package Tool." It is a package management system used in Ubuntu for installing, updating, and removing software packages.

update: it instructs the package management system to update its information about available software packages.

```
rohit@rohit-kumar:~$ sudo apt update
[sudo] password for rohit: 
Sorry, try again.
[sudo] password for rohit: 
Hit:2 http://in.archive.ubuntu.com/ubuntu jammy InRelease                                           
Hit:3 https://dl.google.com/linux/chrome/deb stable InRelease                                       
Get:4 http://in.archive.ubuntu.com/ubuntu jammy-updates InRelease [119 kB]                          
Get:5 http://security.ubuntu.com/ubuntu jammy-security InRelease [110 kB]                           
Hit:6 http://in.archive.ubuntu.com/ubuntu jammy-backports InRelease                                 
Hit:1 https://packages.microsoft.com/repos/code stable InRelease                                    
Get:7 https://apt.packages.shiftkey.dev/ubuntu any InRelease [1,228 B]
Err:7 https://apt.packages.shiftkey.dev/ubuntu any InRelease
  The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 7FC979028B1997C1
Reading package lists... Done
W: GPG error: https://apt.packages.shiftkey.dev/ubuntu any InRelease: The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 7FC979028B1997C1
E: The repository 'https://apt.packages.shiftkey.dev/ubuntu any InRelease' is not signed.
N: Updating from such a repository can't be done securely, and is therefore disabled by default.
N: See apt-secure(8) manpage for repository creation and user configuration details.
```

Step 2: Install Node.js. You can install either the LTS (Long Term Support) or the latest version. Here, I'll show you how to install the LTS version:

```
sudo apt install nodejs
```
sudo: This is a command that stands for "superuser do." It's used to execute the following command with administrative privileges.

apt: Stands for "Advanced Package Tool." It's a package management system used in Ubuntu for installing, updating, and removing software packages.

install: This is a specific sub-command of apt. It tells the package manager that you want to install a software package.

nodejs: This is the name of the software package you want to install. In this case, it's Node.js, a JavaScript runtime for executing JavaScript code on the server side.

```
rohit@rohit-kumar:~$ sudo apt install nodejs
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
nodejs is already the newest version (12.22.9~dfsg-1ubuntu3.4).
0 upgraded, 0 newly installed, 0 to remove and 19 not upgraded.
1 not fully installed or removed.
After this operation, 0 B of additional disk space will be used.
Do you want to continue? [Y/n] y
Setting up install-info (6.8-4build1) ...
/usr/sbin/update-info-dir: 2: /etc/environment: http.proxy=http://rohit19102000kumar@fspl.com:12345@10.10.10.10:3128/: not found
dpkg: error processing package install-info (--configure):
 installed install-info package post-installation script subprocess returned error exit status 127
Errors were encountered while processing:
 install-info
E: Sub-process /usr/bin/dpkg returned an error code (1)
```

Step 3: Additionally, it's a good idea to install npm (Node Package Manager), which is used to install and manage Node.js packages:
```
sudo apt install npm
```

Certainly! Let's break down sudo apt install npm:

sudo: It means "superuser do" and is used to execute the following command with administrative privileges.

apt: Stands for "Advanced Package Tool." It's a package management system used in Ubuntu for handling software packages.

install: This is the sub-command of apt that tells the package manager you want to install a new software package.

npm: This is the specific software package you want to install. In this case, it's the Node Package Manager, used for managing and installing JavaScript packages
```
rohit@rohit-kumar:~$ sudo apt install npm
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
npm is already the newest version (8.5.1~ds-1).
0 upgraded, 0 newly installed, 0 to remove and 19 not upgraded.
1 not fully installed or removed.
After this operation, 0 B of additional disk space will be used.
Do you want to continue? [Y/n] y
Setting up install-info (6.8-4build1) ...
/usr/sbin/update-info-dir: 2: /etc/environment: http.proxy=http://rohit19102000kumar@fspl.com:12345@10.10.10.10:3128/: not found
dpkg: error processing package install-info (--configure):
 installed install-info package post-installation script subprocess returned error exit status 127
Errors were encountered while processing:
 install-info
E: Sub-process /usr/bin/dpkg returned an error code (1)
```

Step 4: Verify that Node.js and npm are installed successfully by checking their versions:
```
node -v
npm - v
```
node -v:
node: This is the command-line interface for Node.js, a JavaScript runtime. It allows you to run JavaScript code outside of a web browser.
-v: This is an option that stands for "version." When you run node -v, it prints out the version of Node.js installed on your system.
In short, node -v tells you the version of Node.js installed on your machine.

npm -v:
npm: Stands for "Node Package Manager." It is a package manager for JavaScript, allowing you to install and manage libraries and frameworks for your Node.js projects.
-v: Similar to the previous example, when you run npm -v, it prints out the version of npm installed on your system.

```
rohit@rohit-kumar:~$ node -v
v20.11.1
rohit@rohit-kumar:~$ npm -v
10.2.4
```

This should display the installed versions of Node.js and npm, respectively.

Now, you have Node.js and npm installed on your Ubuntu system. You can use them to run JavaScript applications and manage packages.

**Install docsify on ubuntu** 

- To install Docsify on Ubuntu, We can follow these steps. Please note that Docsify requires Node.js to be installed, so make sure you have Node.js installed on your system before proceeding. If you haven't installed Node.js yet, you can refer to the previous answer for instructions.

**Here are the steps to install Docsify:**

Open a terminal on your Ubuntu system.

- Use npm (Node Package Manager) to install Docsify globally. This allows you to use Docsify from any directory:
```
sudo npm install -g docsify -cli
```
sudo: This is a command that stands for "superuser do." It's used to execute the following command with elevated or administrative privileges. It's often required when installing global packages or making system-level changes.

npm: Stands for Node Package Manager. It's a tool for managing and installing JavaScript packages.

install: This is an npm command used to install packages.

-g: This is a flag that stands for "global." It tells npm to install the package globally, making it available system-wide rather than just for the current project.

docsify-cli: This is the name of the package being installed. docsify-cli is the command-line interface for Docsify, a documentation site generator.
```
rohit@rohit-kumar:~$ sudo npm install -g docsify -cli
added 9 packages, and audited 10 packages in 6s
```
The -g flag installs the package globally.

- Once the installation is complete, you can verify that Docsify is installed by checking its version:
```
 docsify -V
```

Certainly! The docsify -V command is used to check the version of Docsify installed on your system. Let's break it down:

docsify: This is the command you run in the terminal. It is the executable for Docsify, a tool used to generate documentation websites.

-V or --version: This is an option or flag that you provide to the docsify command. When used, it instructs Docsify to display its version number.


rohit@rohit-kumar:~$ docsify --version

docsify-cli version:
  4.4.4

  This should display the version number of Docsify.

Now that Docsify is installed, you can use it to initialize a new Docsify project or serve an existing documentation project.

- To create a new Docsify project, navigate to the directory where you want to create your documentation and run:
```
 docsify init ./docs
```
docsify: This is the command-line tool for Docsify.

init: This is a command used to initialize or set up a new Docsify project.

./docs: It specifies the directory where the Docsify project will be initialized. In this case, it's creating a Docsify project in the ./docs directory. You can replace ./docs with the path to your preferred documentation directory.
```
root@Hunny:/home/vboxuser# docsify init ./docs
Initialization succeeded! Please run docsify serve ./docs
```


This command initializes a new Docsify project in the ./docs directory. You can replace ./docs with the path to your preferred documentation directory.

- To preview your Docsify documentation locally, run the following command in the same directory:
```
 docsify serve ./docs
```
docsify: Refers to the Docsify command-line tool.

serve: This is a sub-command of Docsify. When you run docsify serve, it starts a local development server.

./docs: Specifies the directory containing your documentation files. In this case, it's the docs directory in the current location (./).

```
rohit@rohit-kumar:~$ docsify serve ./docs
Serving /home/vboxuser/docs now. Listening at http://localhost:3000
```

This will start a local development server, and you can view your Docsify documentation by opening your web browser and navigating to
```
<http://localhost:3000>
```
 http://: This is the protocol used for communication between your web browser and the server. It stands for Hypertext Transfer Protocol.

localhost: This is a special hostname that refers to the current device or computer. In this case, it means you are accessing a web server on your own computer.

:3000: This is the port number. Ports are like different doors on a server that handle specific types of communication. In this case, the web server is set to listen on port 3000.

 Deployment (Optional)

To deploy your documentation, upload the contents of the docs folder to your hosting provider. Docsify doesn't require a server, so you can host it on platforms like GitHub Pages, Netlify, or any other static file hosting service.
![Screenshot from 2024-03-08 15-55-38](https://github.com/rohit1910kmr/docsify_rk/assets/159015754/93448c97-0ec7-44fd-95f7-6ba8418fec0b)






That's it! You have now successfully set up Docsify in Ubuntu. You can begin writing your documentation using Markdown files in the docs directory, and the changes will be reflected in real time on the Docsify server.




