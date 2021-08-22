# Kik Bot API #

This is a modification to kik-bot-api-unofficial and can be used as a spambot.
It uses an updated kik version so you may encounter a captcha while trying to login. 
You can dm me on [@sitiaro](https://kik.me/sitiaro) on kik if you need help with anything related to this or if you want to buy a botnet for kik.

# Features #

Dm commands
```
Friend - To add the bot to your friend list
```

*------------------------*

### Commands ###

Commands to be entered in a public or a private group chat;
```
- Spam group chat/sends a fixed no. of messages; command :: .spam (no. of messages)
 
- Spam group chat/unlimited spam; command :: Spam
 
- Custom spam (group chat); command :: .cs/message_here
```

# Note #

New changes randomize the device and android id and that might lead to the accounts getting banned faster, so it's recommended to use a newly made account. 

*------------------------*

## Installation and dependencies ##

First, make sure you are using **Python 3.6+**, not python 2.7 or python 3.9. Linux follows a different procedure and it's listed below'.


** (Do this before installing the api/more on how to get python 3.8 below.)

If you are using [Termux](https://termux.com/), then use `pkg install libxml2 libxslt` to install `lxml` and `pkg install zlib libpng libjpeg-turbo` to install `pillow` dependencies.

## Installation ## (this may take a while so be patient)
```
$ git clone https://github.com/Sitiaro/kikspambot **
```
```
$ pip install ./kikspambot
```
## Usage ##
```
$ cd kikspambot
```
```
$ python spambot.py
```
Login with the username and password of your spam account, add it to your friend list by typing 'friend' in the bot's dms and add it to the chat you want to spam. 
Once you do so, use 

.spam (no. of messages) 

to spam the chat. For infinite spam, use 'spam' without quotes in a group chat.

You can use the below mention command to spam a custom text infinitely;
```
$ .cs/(whatever you want to spam)
```
## This may lead to your account getting banned from kik so use it at your own expense. ##


## Replacing python 3.9 with 3.8 ##

(Termux)

Uninstall python -
```
$ pkg uninstall python
```
Check the arch of your device cpu using -
```
$ uname -m
```
Go to https://github.com/Termux-pod/termux-pod and find the file corresponding to your device's CPU. You should try python_3.8.6_.deb first and then the static version if there is any error.

Download the raw .deb file corrosponding to your arch and follow the next steps to replace whatever python you have with python 3.8.x.
```
$ cd /sdcard/Download
```
```
$ dpkg -i ./python_3.8.6_<CPU_ARCH.>.deb
```
Once again, replacing <CPU_ARCH.> with your cpu's architecture.


# Adding python 3.8 to Linux #

Head over to https://www.python.org/downloads/release/python-386/ 
Scroll down and download XZ compressed source tarball. Once it finishes download, open your downloads, right click on the compressed python folder, and click extract to > Desktop. Once it finishes, open your terminal and cd to that python directory that's on your desktop. Once you're into that directory, run the following commands one at a time (will take time):
```
$ sudo su 
```
or
```
$ su root
```
(will ask you for your root password, enter it and proceed to the next step)
```
$ ./configure
```
```
$ make install
```
## Installation ## (this may take a while so be patient)
```
$ git clone https://github.com/Sitiaro/kikspambot **
```
```
$ pip3 install ./kikspambot
```
## Usage ##
```
$ cd kikspambot
```
```
$ python3.8 spambot.py
```
Login with the username and password of your spam account, add it to your friend list by typing 'friend' in the bot's dms and add it to the chat you want to spam. 
Once you do so, use 

.spam (no. of messages) 

to spam the chat. For infinite spam, use 'spam' without quotes in a group chat.

You can use the below mention command to spam a custom text infinitely;
```
$ .cs/(whatever you want to spam)
```
*------------------------*
