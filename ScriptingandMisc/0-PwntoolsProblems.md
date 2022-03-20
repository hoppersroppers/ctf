# Pwntools Problems
##  [Register for the Free Course Today!](https://www.roppers.org/courses/ctf)
A common scripting problem is connecting to web socket/SSH server and then doing some scripted activity. You should implement these problems using Pwntools rather than trying to make your own with Python sockets or gasp, something in C. <https://github.com/Gallopsled/pwntools>


For this section, write a script using pwntools that connects to a port, waits for the word "Username:", enters "root", waits for "Password:", enters "root", then takes in 2 numbers, adds them together, and returns the solution. 

I'm not giving you the "server" for this challenge, so you're going to have to write your own server to test this. Write up a server that only accepts root/root as the user/pass and then gives two random numbers and checks that the response is correct. 

To host the server locally for testing, run '''socat TCP-LISTEN:1337,fork EXEC:'/path/to/script',stderr,pty,echo=0'''.