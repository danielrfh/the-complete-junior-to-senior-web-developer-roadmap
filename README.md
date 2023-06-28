# The Complete Junior to Senior Web Developer Roadmap

All resources and notes from the [The Complete Junior to Senior Web Developer Roadmap](https://zerotomastery.io/courses/junior-to-senior-web-developer-roadmap/)

- [The Complete Junior to Senior Web Developer Roadmap](#the-complete-junior-to-senior-web-developer-roadmap)
  - [**Introduction**](#introduction)
  - [**SSH**](#ssh)
    - [Resources: SSH Command](#resources-ssh-command)
    - [Optional: Digital Ocean Set Up](#optional-digital-ocean-set-up)
    - [Optional: Digital Ocean Server](#optional-digital-ocean-server)
    - [Resources: Asymmetric Encryption](#resources-asymmetric-encryption)
    - [Quick Note: SSH Into A Server](#quick-note-ssh-into-a-server)
    - [Resources: SSH Into A Server](#resources-ssh-into-a-server)
    - [Extra Solution: Set Up SSH on Github](#extra-solution-set-up-ssh-on-github)
  - [**Performance Part 1**](#performance-part-1)
    - [3 Keys To Performance](#3-keys-to-performance)
    - [Network Performance](#network-performance)
    - [Image File Formats](#image-file-formats)
    - [Resources: Image File Formats](#resources-image-file-formats)
    - [Image Optimizations](#image-optimizations)
    - [Resources: Delivery Optimizations](#resources-delivery-optimizations)
    - [Resources: Async + Defer](#resources-async--defer)
    - [Resources: Performance Tools](#resources-performance-tools)
  - [**OPTIONAL: React + Redux + Module Bundling**](#optional-react--redux--module-bundling)
  - [**Performance Part 2**](#performance-part-2)
  - [**Testing**](#testing)
  - [**TypeScript**](#typescript)
  - [**SPA vs Server Side Rendering**](#spa-vs-server-side-rendering)
  - [**Security**](#security)
  - [**Code Analysis**](#code-analysis)
  - [**Docker**](#docker)
  - [**Redis**](#redis)
  - [**Sessions + JWT**](#sessions--jwt)
  - [**AWS**](#aws)
  - [**Performance Part 3**](#performance-part-3)
  - [**CI/CD**](#cicd)
  - [**Extra Bits**](#extra-bits)
  - [**The Final Video**](#the-final-video)
  - [**Extras: For Windows Users**](#extras-for-windows-users)
  - [**Bonus: AMA Video!**](#bonus-ama-video)

## **Introduction**

[Don't Be A Junior Developer](https://zerotomastery.io/blog/dont-be-a-junior-developer-the-roadmap)

## **SSH**

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

## **Performance Part 1**

### 3 Keys To Performance

**Frontend:**

- Critical Render Path
- Optimized Code
- Progressive Web App

**Network:**

- Minimize Files
- Minimize Delivery

**Backend:**

- CDNs
- Caching
- Load Balancing
- DB Scaling
- GZIP

### Network Performance

- Minimize Text (JS, CSS, HTML)
  - <https://skalman.github.io/UglifyJS-online/>
- Minimize Images (JPG)

### Image File Formats

- JPG: Usually used for photos, images with no transparency.
- GIF: Limited number of colors and used for small animations.
- PNG: Limited number of colors, usually used for logos and can add transparency.
- SVG: Vector graphics with small size and greatly scalable.

### Resources: Image File Formats

<https://99designs.com/blog/tips/image-file-types/>

<https://pageweight.imgix.com/>

<https://www.sitepoint.com/gif-png-jpg-which-one-to-use/>

Additionally, here are some extra resources:

<https://www.verexif.com/en/>

<https://css-tricks.com/snippets/css/media-queries-for-standard-devices/>

[Media Queries Cheat Sheet](https://gist.github.com/bartholomej/8415655)

### Image Optimizations

- If you want transparency: use a PNG.
- If you want animations: use a GIF.
- If you want colorful images: use a JPG.
- If you want simple icons, logos and illustrations: use SVG.
- Reduce PNG with [TinyPNG](https://tinyjpg.com).
- Reduce JPG with [JPEG-optimizer](http://216.92.55.187).
- Try to choose simple illustrations over highly detailed photographs.
- Always lower JPEG image quality (30-60%).
- Resize image based on size it will be displayed.
- Display different sized images for different backgrounds.
- Use CDNs like [imigx](https://imgix.com).
- Remove image metadata

### Resources: Delivery Optimizations

<https://stackoverflow.com/questions/985431/max-parallel-http-connections-in-a-browser>

### Resources: Async + Defer

<https://stackoverflow.com/questions/10808109/script-tag-async-defer>

### Resources: Performance Tools

[PageSpeed Insights](https://pagespeed.web.dev/)
[WebPageTest](https://www.webpagetest.org/)

## **OPTIONAL: React + Redux + Module Bundling**

## **Performance Part 2**

## **Testing**

## **TypeScript**

## **SPA vs Server Side Rendering**

## **Security**

## **Code Analysis**

## **Docker**

## **Redis**

## **Sessions + JWT**

## **AWS**

## **Performance Part 3**

## **CI/CD**

## **Extra Bits**

## **The Final Video**

## **Extras: For Windows Users**

## **Bonus: AMA Video!**

[def]: #typescript
