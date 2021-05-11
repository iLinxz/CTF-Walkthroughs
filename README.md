# Hello, World!

This branch is reserved for all sorts of useful resources and cheatsheets I found on the internet. Some cheatsheets created by yours truly.


## SQL Injection Cheatsheet <--> **Credits to John Hammond :D**
> www.github.com/JohnHammond/miscellaneous/blob/master/SQL_INJECTION_CHEATSHEET.md

I have used this cheatsheet in many of my engagements whenever SQL injection was the way to exploit my victim. It is not a big cheatsheet by any means but it is very helpful, easy to understand and to apply.

## PayloadAllTheThings Git Repo
> www.github.com/swisskyrepo/PayloadsAllTheThings

This is a GitHub repository that is full  of, as the name suggests, payloads. This is a very exhaustive list of payloads in all shapes and sizes. Whenever you find yourself at the weaponization stage of an engagement, make sure to give this a look.
Within this GitHub repository, a big number of other types of cheatsheets can be found, from methodology and enumeration cheatsheets to  network pivoting techniques, Active Directory attacks and even more. You can even find exploits based on their respective CVE number.

## Reverse Shell Generator
>www.revshells.com

This website is an automated tool to generate reverse shell payloads. It has an easy to understand user interface and lots of ways to create a reverse, bind or even a MSFVenom shell payload. It is a complex and easy to use resource that saves you time and adds a customability factor to your work.

## GCHQ's CyberChef
>www.gchq.github.io/CyberChef

This is a GitHub repository created by UK's cyber security elite: GCHQ. It is a repository that handles the encryption and decryption in various ways of any type of data. You will be spending lots of time here if you are doing cryptography based challenges.

## GTFO Bins
>www.gtfobins.github.io

When you find yourself in need of escalating your privilleges, look no further. This GitHub repository hands you all the solutions you need. This repository is full of ways in which one can escalate his/her privilleges depending on what binary files are found on the victim system. Easy to use and follow. Highly recommend.

## LFI PHP Filter
>www.example.com/vulnerable.php?=php://filter/convert.base64-encode/resource=index.php
```
php://filter/convert.base64-encode/resource=
```
This filter helps an attacker view the contents of any .php file without actually making the server execute said file when it is called. The attacker will be presented with a bunch of base64 characters. If they are decoded, the decoded message is exactly the contents of whatever .php file was called.
In the example above, the result of that request will be just a bunch of base64 characters which I will have to decrypt using CyberChef. At the end of the decryption process, I will be presented with the whole index.php file  exactly as it is written in php format.
