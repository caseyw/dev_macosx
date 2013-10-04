# Our Base Mac OSX Setup

## Base Command Line

### Xcode

This will grant you the most predictable behavior in building apps like MacVim.

How do you do it?

1. Install Xcode from the Mac App Store.
1. Open Xcode.
1. Open the Preferences window (`Cmd-,`).
1. Go to the Downloads tab.
1. Install the Command Line Tools.

### iTerm2

iTerm2 is a replacement for the OSX terminal. It does do amazing things :)

Install it like other compiled binaries.

http://www.iterm2.com/#/section/downloads

Launch it through Launchpad

### Homebrew

Homebrew allows us to install packages in a similar way as apt-get on Ubuntu.

How do you install it?

1. Open your new iTerm2 terminal
1. Run command 

```
ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
```

Once complete you can verify it installed by running:

```
brew -v
```

## Developement Tools

### Virtual Box

VirtualBox is a virtualization package that allows us to spin up various types of machines to develop on.

Install the newest OSX version here.

https://www.virtualbox.org/wiki/Downloads

Launch it through Launchpad

### Vagrant

Vagrant allows us to:

"Create and configure lightweight, reproducible, and portable development environments."

Install the newest OSX version here.

http://downloads.vagrantup.com/

```
vagrant -v
```

## IDE / Code Editing

### PhpStorm

PhpStorm is my current main code editor. I used Netbeans for years, and upon trying PhpStorm for 10m I switched over.

Install the newest OSX version here.

http://www.jetbrains.com/phpstorm/download/index.html

Launch it through Launchpad

### SublimeText3

SublimeText is one of those quick edit tools, and I know many who use it as their main editor.

Install the beta here.

http://www.sublimetext.com/3

Launch it through Launchpad

Tip: Create a symlink so that you can open files on the command line. You'll need to type in your password.

```
sudo ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /bin/subl
```

After that runs, you'll need to restart your terminal.

Edit a file:

```
subl filename.txt
```

Open a directory in project view:

```
subl ~/path/to/directory
```

## Databases

### MySQL Workbench

Nice MySQL tool for working on queries, peeking in on processes and all that juicy stuff.

Install the newest OSX version here.

http://dev.mysql.com/downloads/tools/workbench/

Can my used through Launchpad

## Misc (Things I like)

### Nyan Cat. Yes. I said it.

http://www.nyan.cat/

### Oh My ZSH

Look into it yourself, and see if it's a good fit.

https://github.com/robbyrussell/oh-my-zsh

### Alfred App, like Quicksilver but better (Paid app, but worth it)

Alfred is an award-winning productivity application for Mac OS X

Alfred saves you time when you search for files online or on your Mac. Be more productive with hotkeys, keywords and file actions at your fingertips.

My description provides a simple example. In the morning when I get on my cold computer before I shackle myself to it. I hit my hotkey that brings up Alfred. I type "St", it autocompletes asking if I was to "Start my day". I hit enter and it proceeds to open Email, JIRA, iTerm2, Skype, PhpStorm and Sublime.

I'm able to walk away, get something to drink and when I get back all my tools are open and ready for me.

Another example is when I want to jump into a JIRA ticket, I do my hotkey again, type "j TICKET". It opens the browser, and shows me the ticket I entered. Pretty slick and saves a lot of time overall.

http://www.alfredapp.com/

