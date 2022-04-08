# CSE15L Week 2 Lab Report

1. Installing VScode

Go to [https://code.visualstudio.com/](https://code.visualstudio.com/) and install Visual Studio Code for your operating system. After installing, VSCode will look something like this:

![VSCode Website]()

Your VSCode's theme and buttons may differ by your computer's operating system or environment.

2. Remotely Connecting

>Extra steps for Windows users: [Install OpenSSH via this link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)

Open terminal on VSCode by clicking Terminal -> new Terminal from the menu, and remotely connect to your remote student server using the command `ssh cs15lsp22zz@ieng6.ucsd.edu`, where `zz` is replaced with your student account.

When connecting to the server for the first time, there may be a message like this:

```
$ ssh cs15lsp22zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])?
```

Just type `yes` and press enter to these type of messages.

After that, you will be prompted to type your password. Enter your password and press enter.

A successful connection would look something like this:

![Screenshot of connecting via ssh]()


3. Trying Some Commands

![Screenshot of commands]()

Here is a list of commands and what they do:
```
command - what they do
command - what they do
```

4. Moving Files with scp

`scp "filename" cs15lsp22zz@ieng6.ucsd.edu:~/` move files to the server using this command.

![Screenshot of scp file moving]()

5. Setting an SSH Key

![SSH key setup screenshot]()

6. Optimizing Remote Running

>Hint: We can use `;` between commands and `"command; command"` to have the command run remotely

![screenshot of my optimization]()

For example, I reduced `some command` and `some command` to a single line of command `some command` using this. Considering I have the command pre-run beforehand, I can reduce the total keystroke to complete these actions into two keystrokes.
