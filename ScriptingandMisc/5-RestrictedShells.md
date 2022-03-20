# Restricted Shells
##  [Register for the Free Course Today!](https://www.roppers.org/courses/ctf)
[Restricted shells](https://en.wikipedia.org/wiki/Restricted_shell) are a classic CTF problem because they're actually a classic security problem. Since the dawn of shared computing, situations have existed where you want to give a user access to a server, but restrict their ability to run certain commands or read certain files, or sometimes do things like run commands with specific characters or words. I think  that restricted shells and privilege escalating out of the them is the purest form of CTF challenge. 

For these challenge you'll be given a username and pass to a service and then have to find your way out. 95% of the time, something in [this guide to escapes](https://www.exploit-db.com/docs/english/44592-linux-restricted-shell-bypass-guide.pdf) will tell you what you need to do. 

Read the whole guide and try to understand what the different things mean. If you don't understand why a specific bypass works, do some research. 

Something that helps when you're working on these problems is once you figure out which type of restricted shell you are in, go and find the original source code on Github and try to determine what modifications the challenge author made to the problem. Once you've found what makes the challenge unique, you've probably found the vulnerable section.

If you're stuck with one of these problems and can't figure it out, it's probably ENV variables. It's always ENV variables. 
