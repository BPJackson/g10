
3) Install Homebrew
Homebrew is a tool that will allow you to easily install development tools to your Mac from source code.
You will follow the instructions on the website to get it installed. When prompted to enter your password, use the password that you use to unlock your computer. When you are asked to install the command line tools, click the "Install" button. You do not need to install a full copy of XCode. Copy the code below into the terminal to begin installing.

$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
==> This script will install: < lots of output > You should run brew doctor before you install anything. Now type: brew help

$ brew help
Example usage:
< lots of output >
When the installation is complete, you should use brew doctor to make sure everything is running smoothly.

$ brew doctor
Your system is ready to brew.

4) Install and Configure git
$ brew install git

Setting your name:
 $ git config --global user.name "Your Name Here"
This should be your first and last name, not your system or GitHub username.

Setting your email:

$ git config --global user.email "your_email@example.com"
It is important that this email is the same as the email you used to sign up for GitHub. For more information: http://git-scm.com/book/en/Getting-Started-First-Time-Git-Setup

5) Set up global gitignore file
Sometimes there are files or directories that you never want to add to git source control so you ignore them. The easiest way is to set up a global gitignore:

Create a .gitignore_global in your root directory bash $ touch ~/.gitignore_global Put the text '.idea/' into the global gitignore file.

$ echo ".idea/" >> ~/.gitignore_global
Tell git to use that file as the global gitignore.

$ echo '.DS_Store' >> ~/.gitignore_global
$ echo 'junk.* ' >> ~/.gitignore_global
$ git config \--global core.excludesfile ~/.gitignore_global

6) Install Node & NPM (Node Package Manager)
brew install node
  Run node -v. The output should be v0.12.0 or similar.
  Run npm -v. The output should be 2.5.1 or similar.

7) Generate an SSH key
Quick Rundown:
  ssh-keygen -t rsa -C "your_email@example.com" and hit ENTER three (3) times.
  eval "$(ssh-agent -s)"
  ssh-add ~/.ssh/id_rsa
  Copy key to clipboad: pbcopy < ~/.ssh/id_rsa.pub
  In Github, Settings -> SSH -> Add SSH Key -> Add Key

If you run the cd ~/.ssh command and you get the message that looks like -bash: cd: /Users/user/.ssh: No such file or directory, you don't have an ssh key and you can continue to step 2. When you get to step 2, the ssh-add command should look like this:

$ ssh-add ~/.ssh/id_rsa
If you already have an SSH key as identified by step 1, please make sure that you add a password to the key using this guide before continuing to step 3.



1. HTML FORMS
2. Javascript DOM
