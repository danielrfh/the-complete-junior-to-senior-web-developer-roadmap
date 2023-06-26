# The Complete Junior to Senior Web Developer Roadmap

All resources and notes from the [The Complete Junior to Senior Web Developer Roadmap](https://zerotomastery.io/courses/junior-to-senior-web-developer-roadmap/)

- [The Complete Junior to Senior Web Developer Roadmap](#the-complete-junior-to-senior-web-developer-roadmap)
  - [__Introduction__](#introduction)
  - [__SSH__](#ssh)
    - [Resources: SSH Command](#resources-ssh-command)
    - [Optional: Digital Ocean Set Up](#optional-digital-ocean-set-up)
    - [Optional: Digital Ocean Server](#optional-digital-ocean-server)
    - [Resources: Asymmetric Encryption](#resources-asymmetric-encryption)
    - [Quick Note: SSH Into A Server](#quick-note-ssh-into-a-server)
    - [Resources: SSH Into A Server](#resources-ssh-into-a-server)
    - [Extra Solution: Set Up SSH on Github](#extra-solution-set-up-ssh-on-github)
  - [__Performance Part 1__](#performance-part-1)
  - [__OPTIONAL: React + Redux + Module Bundling__](#optional-react--redux--module-bundling)
  - [__Performance Part 2__](#performance-part-2)
  - [__Testing__](#testing)
  - [__TypeScript__](#typescript)
  - [__SPA vs Server Side Rendering__](#spa-vs-server-side-rendering)
  - [__Security__](#security)
  - [__Code Analysis__](#code-analysis)
  - [__Docker__](#docker)
  - [__Redis__](#redis)
  - [__Sessions + JWT__](#sessions--jwt)
  - [__AWS__](#aws)
  - [__Performance Part 3__](#performance-part-3)
  - [__CI/CD__](#cicd)
  - [__Extra Bits__](#extra-bits)
  - [__The Final Video__](#the-final-video)
  - [__Extras: For Windows Users__](#extras-for-windows-users)
  - [__Bonus: AMA Video!__](#bonus-ama-video)

## __Introduction__

[Don't Be A Junior Developer](https://zerotomastery.io/blog/dont-be-a-junior-developer-the-roadmap)

## __SSH__

### Resources: SSH Command

**Windows:**  
Use PuTTY: <https://mediatemple.net/community/products/dv/204404604/using-ssh-in-putty->

Windows 10: <https://www.howtogeek.com/336775/how-to-enable-and-use-windows-10s-built-in-ssh-commands/>

Extra:  

1. <https://www.ssh.com/ssh/putty/windows/>
2. <https://www.memset.com/docs/server-security/secure-communication-ssh/using-ssh-windows/>

**Linux:**  
You should be able to use the ssh command already, but in case you can't:
<https://www.makeuseof.com/tag/beginners-guide-setting-ssh-linux-testing-setup/>

### Optional: Digital Ocean Set Up

More information on apt-get : <https://help.ubuntu.com/community/AptGet/Howto>  
More information on rsync : <https://www.tecmint.com/rsync-local-remote-file-synchronization-commands/>

### Optional: Digital Ocean Server

<https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-16-04>

### Resources: Asymmetric Encryption

Want to learn more about Asymmetric Encryption? Check out these extra videos :
<https://www.youtube.com/watch?v=NmM9HA2MQGI>  
<https://www.youtube.com/watch?v=Yjrfm_oRO0w>  
<https://www.youtube.com/watch?v=vsXMMT2CqqE&t=>  
<https://www.youtube.com/watch?v=NF1pwjL9-DE>  

### Quick Note: SSH Into A Server

Also, if you are on Windows, you may have to use GitBash instead of Powershell. Here are the steps that a fellow student followed:

1. Download, install and open Git Bash - the link is provided at the end of the video.
2. Type `ssh-agent bash` and press Enter.
3. Type `ssh-add ~/.ssh/id_rsa_digitalocean` and press Enter. You should get confirmation of Identity added.
4. Try connecting to your digital ocean account again via SSH. Now it shouldn't ask you for the password!

### Resources: SSH Into A Server

**Recommended `ssh-keygen` command:**
  
`ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`

**Windows:**  
If you have Git for Windows (which you should), ssh-keygen command should be available: <https://gitforwindows.org/>  
You can read more about this here:
<https://stackoverflow.com/questions/11771378/ssh-keygen-is-not-recognized-as-an-internal-or-external-command>

Another option is to use <https://www.ssh.com/ssh/putty/windows/puttygen>

`pbcopy` command: <https://superuser.com/questions/472598/pbcopy-for-windows/1171448#1171448>  

**Extra Video:**  
If you want to learn a little bit more about how SSH works internally, watch this excellent video: <https://youtu.be/ORcvSkgdA58>  

### Extra Solution: Set Up SSH on Github

Here is a great visual guide created by a fellow student if you are still having problems solving this exercise (especially on Windows):  
<https://github.com/antonykidis/Setup-ssh-for-github/blob/master/Setup-ssh-on-github.pdf >

## __Performance Part 1__

## __OPTIONAL: React + Redux + Module Bundling__

## __Performance Part 2__

## __Testing__

## __TypeScript__

## __SPA vs Server Side Rendering__

## __Security__

## __Code Analysis__

## __Docker__

## __Redis__

## __Sessions + JWT__

## __AWS__

## __Performance Part 3__

## __CI/CD__

## __Extra Bits__

## __The Final Video__

## __Extras: For Windows Users__

## __Bonus: AMA Video!__

[def]: #typescript