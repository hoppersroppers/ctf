# Language Problems

Sometimes CTF challenge writers don't want to hurt your head with a
normal language like C or Python, and instead give you something
completely random.

Sometimes it will be old programming languages, like FORTRAN or ADA. If
you see a language that you don't recognize, look for something that
appears to be the main function or a loop, basically any construct you
recognize, and google it. If it is an important piece of the language,
someone has mentioned it before and you'll at least know the language
name. From there, you have to find some old documentation (or hopefully
example code on Github) to copy. You'll have to find a compiler on
Github to test them, and getting the entire toolchain to work is a real
pain. These challenges are crazy hard, but it feels awesome when you get
a punchcard program to compile.

Another classic is esoteric programming languages, which are defined by
Wikipedia as " designed to test the boundaries of computer programming
language design, as a proof of concept, as software art, as a hacking
interface to another language (particularly functional programming or
procedural programming languages), or as a joke." As most things are
Turing Complete if you try hard enough (look it up if you don't know
what that means, basically anything can be a programming language. Good
for challenge developers, bad for you. For the most part though, they'll
be using a well-known esoteric like
<a href="https://en.wikipedia.org/wiki/Brainfuck"
target="_blank">brainfuck</a>, or any of the other languages listed on
<a href="https://en.wikipedia.org/wiki/Esoteric_programming_language"
target="_blank">this wiki page</a>. Writing your own esoteric for a CTF
is a lunatic move, so if you see something that doesn't match any of
these formats, expect it to be a substitution version of an existing
language, so look for syntactical similarities and throw it into an
existing interpreter once you've translated it over.

<img
src="https://files.cdn.thinkific.com/file_uploads/429463/images/1ef/4fe/565/1645995136064.jpg"
class="fr-dib"
srcset="https://files.cdn.thinkific.com/file_uploads/429463/images/1ef/4fe/565/1645995136064.jpg?width=1920 1x, https://files.cdn.thinkific.com/file_uploads/429463/images/1ef/4fe/565/1645995136064.jpg?width=1920&amp;dpr=2 2x, https://files.cdn.thinkific.com/file_uploads/429463/images/1ef/4fe/565/1645995136064.jpg?width=1920&amp;dpr=3 3x"
style="width: 69px;" />

Another really common challenge is using an alphabet from another
language, especially fictional and scifi ones. For those, use a site
named <a href="https://omniglot.com/conscripts/fictional.htm"
target="_blank">omniglot</a> to get a comprehensive list with examples.
As a fun note, you don't actually need to know the language to solve
problems like this. As long as it is a standard 26 character alphabet,
you can solve any made up language like a substitution cipher using
standard cryptographic tools, just map each made up character to a real
character and treat it like a substitution.

This is all to test your out of the box thinking and ability to learn
quickly. It's terrible but they are actually kind of fun.

1.  Decrypt this:
    ++++++++++\[\>+\>+++\>+++++++\>++++++++++\<\<\<\<-\]\>\>\>+++.\<+++++++++.\>\>+++++++++.\<\<-------.\>\>++++++.----.+++..+++++++.\<\<++++++++++++.------------.\>.\<.\>\>---------------------.+++++++++++.-.\<\<+++++++.\>\>++++++.\<\<-------.\>\>--------.---.++.------.\<\<.\>\>+++++++++++++++.------------.+.++++++++++.\<\<.\>\>------------.------.++++++++++++.--------.\<\<++++++++++++++.

Then follow this writeup for "Brainmeat":
<a href="https://link.medium.com/qCZhPmtBqib"
target="_blank">https://link.medium.com/qCZhPmtBqib</a>
