# Network Scripting with Pwntools

This is heavily covered in the [Networking
Course](https://www.roppers.org/courses/networking) if you want to
become an expert.

  

If you just want to move forward (for now), try this example problem. 

  

A common scripting problem is connecting to web socket/SSH server and
then doing some scripted activity. One critical tip to this is to spend
some serious time trying to figure out everything the server does/time
outs/etc. Plenty of times you can just get good at whatever task needs
to be scripted, or copy/paste it into a different tool then back in, so
you can avoid scripting altogether. Butttt, if the lazy ways don't work,
it's time for some scripting.

You should implement these problems using Pwntools rather than trying to
make your own with Python sockets or gasp, something in C.
<a href="https://github.com/Gallopsled/pwntools"
target="_blank">https://github.com/Gallopsled/pwntools</a>

For this section, write a script using pwntools that connects to a port,
waits for the word "Username:", enters "root", waits for "Password:",
enters "root", then takes in 2 numbers, adds them together, and returns
the solution. 

I'm not giving you the "server" for this challenge, so you're going to
have to write your own server to test this. Write up a server that only
accepts root/root as the user/pass and then gives two random numbers and
checks that the response is correct. Learning how to write both sides of
this is pretty important.

To host the server locally for testing, run '''socat
TCP-LISTEN:1337,fork EXEC:'/path/to/script',stderr,pty,echo=0'''.

Submit your script.
