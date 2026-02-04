
## x)Install Debian on VirtualBox

- Download the official Debian ISO (live image) for the version you want.
- Install VirtualBox on your host system if not already installed.
- In VirtualBox, create a new VM: choose Linux → Debian (64-bit), assign RAM and create a virtual hard disk.
- Attach the Debian ISO as a virtual CD/DVD in VM settings.
- Boot the VM and choose Live mode to test or install Debian.
- Run the installer, choose language, location, keyboard, partition disk, set user and password, then install.
- If the VM shows a black screen after install, use the xforcevesa boot option fix (optional).
- After installation, log in and update the system (sudo apt-get update and sudo apt-get dist-upgrade).
- Optionally install VirtualBox Guest Additions for better screen resolution and shared clipboard.

**My experience while installing:**
I couldn't use the virtual box, because of my operating system, I have snapdragon, which recently came to market. So, I tried downnloading ubuntu, debian, both virtualbox(arm & amd version) mine is arm-based system in a windows, terchnical both doesn't work for some reason, I did some reseach and found out they have a beta version of virtualbox, but I couldn't find it lol. so, I am still waiting of the actual version to publish in their website.
I used WSL with debian app from microsoft store, it's basically a toy version of the actual linux server, where you could text out commands and check out what you want to do in a safe environment for beginnners who just started using, afraid to try in linux.
anyways you can use if you have my same situation. it's a great tool to play around.

**Command Line Basics Revisited
exploring the filesystem:-
pwd, ls, cd, 
file and directory operations:-
cp, mv,mkdir, rm, rm -r
Remote control and help:-
SSH - ssh user@host
SCP - Copy files to/from remote securely.
Filesystem locations:- 
/ - root of the filesystem
/home/yourname - your user files
/etc/ - system configuration
/var/log/ - logs
basics:-
sudo - run commands as superuser


## a)Disabling Networking and Testing Connectivity in Linux
<img width="1054" height="530" alt="Screenshot 2026-02-04 145507" src="https://github.com/user-attachments/assets/b0745dd5-bb9c-4033-83dc-c1bc1c1b92f8" />

## b) Install Nmap
<img width="1670" height="495" alt="Screenshot 2026-02-04 155837" src="https://github.com/user-attachments/assets/a09212b7-4510-4d02-ae47-532432afa90b" />
<img width="1457" height="1048" alt="Screenshot 2026-02-04 155858" src="https://github.com/user-attachments/assets/45574ea6-a48c-4730-be7a-06610486ab3f" />

## Local Port Scanning on Linux Using Localhost
<img width="1295" height="226" alt="Screenshot 2026-02-04 162324" src="https://github.com/user-attachments/assets/c376507a-5295-438d-b3ee-0a11cca5be1e" />

## c) Daemon scan
<img width="1048" height="459" alt="Screenshot 2026-02-04 163907" src="https://github.com/user-attachments/assets/455e91f5-4274-400e-a954-9a71999a490f" />

## d) Level Passwords
## 0)
<img width="1239" height="401" alt="Screenshot 2026-02-04 165454" src="https://github.com/user-attachments/assets/db0ee1c5-49f0-4427-9a0b-6261280ca02a" />

## 1)
<img width="714" height="96" alt="Screenshot 2026-02-04 171122" src="https://github.com/user-attachments/assets/834b548a-8db3-44f0-bb0f-97432fea1d6e" />

## 2)
<img width="1343" height="130" alt="Screenshot 2026-02-04 172410" src="https://github.com/user-attachments/assets/1777914e-3eea-436f-84c3-4b32a94b2248" />

## 3)
<img width="718" height="273" alt="Screenshot 2026-02-04 173935" src="https://github.com/user-attachments/assets/e5684c49-3b5e-4595-802c-5f9c28b538e7" />

## 4)
![WhatsApp Image 2026-02-04 at 17 42 39](https://github.com/user-attachments/assets/cb5877d5-680a-4245-a91e-4af8167cc518)

## references
https://overthewire.org/wargames/bandit/bandit1.html

https://terokarvinen.com/2020/command-line-basics-revisited/

https://terokarvinen.com/2021/install-debian-on-virtualbox/







