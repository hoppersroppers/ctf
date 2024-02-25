# Things You Shouldn't Try to Do

Remember what we said earlier about how math will win, every time?

The corollary to the rule that you cannot beat math is "Never roll your
own crypto". <a
href="https://www.vice.com/en_us/article/wnx8nq/why-you-dont-roll-your-own-crypto"
target="_blank">https://www.vice.com/en_us/article/wnx8nq/why-you-dont-roll-your-own-crypto</a>.
Anybody can write their own crypto libraries, but it probably sucks and
is susceptible to attacks that were known in 1942. So when you see a CTF
challenge with a "custom encryption library", know that whoever wrote
that library implemented it wrong. In order to solve that challenge, you
will need to know a great deal more about crypto than this course will
try to teach you. If you want to become very very good at crypto, do the
Matasano CryptoPals challenges. <a href="https://cryptopals.com/"
target="_blank">https://cryptopals.com/</a> and spend the rest of your
days reading academic papers. Otherwise, just move on with your life.

So moving on, if implemented properly (and the assumption for all
standard libraries is that they are), the attacker will not beat math.
It doesn't matter if you spin up a cloud server or build a facility in
Utah, you're not going to beat math. Anytime you find yourself trying to
do any of these things, assume that you have gone wrong somewhere along
the way.

1.  Reverse a hash
    -   If nothing comes up when you google for it, move on. This is not
        what you are supposed to solve.
2.  Create a hash collision
    -   Possible for MD5 and SHA1 in various ways. Read this for more
        info: <a href="https://github.com/corkami/collisions"
        target="_blank">https://github.com/corkami/collisions</a>
3.  Crack a password that is longer than 8 characters
    -   The math just isn't there. You are missing something.
    -   That something might just be a wordlist gathered from all words
        on a website/server/description
4.  <a href="https://en.wikipedia.org/wiki/Halting_problem"
    target="_blank">https://en.wikipedia.org/wiki/Halting_problem</a>
5.  <a href="https://en.wikipedia.org/wiki/P_versus_NP_problem"
    target="_blank">https://en.wikipedia.org/wiki/P_versus_NP_problem</a>

  

If you want to get really good at Cryptography, check out this link:
<https://www.hoppersroppers.org/roadmap/training/crypto.html> 

Finish this course first though.
