# CTF Meta

Host forensics, aka "finding something in a file, folder, or
filesystem", is a critical part of real world Blue Team work. In the
course of an incident response, a critical first step is to capture a
copy of the computer that was hacked so that defenders can go over the
filesystem to look for badness. In this course, I am going to skip over
the filesystem bit at first and go straight to looking at individual
files, mostly because learning what to do with funky files is a core
competency of all security experts, and many CTF challenges turn into
file forensics problems once you get past the first layer.

To be up front, forensics is the most hated of all CTF problem types.
This is not because the problems are particularly hard or boring, but is
because some people who make the problems are lazy and make it into a
dumb guessing game. I mentioned earlier that CTF challenges can be
guessy and annoying, mostly based on how well the challenge was
written... and these are the easiest challenges to make... sooo....

Personally, forensics problems are my favorite category. It's the one
that has the most applicability to real world jobs, is super easy to get
started, and when the problems are done correctly, it is basically like
solving a mystery.

There are a few categories of forensic problems that we will go over in
this course, focusing on the ones that we see in CTF problems the most
frequently. None of this should be confused with what actual forensic
analysts do in an incident response, however, many of the skills overlap
and there are some fundamental theories that can be applied to CTF
problems.
