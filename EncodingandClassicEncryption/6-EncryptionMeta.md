# Encryption Meta

<iframe allowfullscreen class="fr-draggable" height="360" src="https://www.youtube.com/embed/Z5UgCQ6SavM?wmode=opaque" width="640"></iframe>  

  

So encoding is nice, because once we identify what type of encoding it
is, the hard part is figuring out what decoder to use.... decryption
is... not as simple. Not just do you need to figure out which type of
encryption is being used, you also need the secrets required to decrypt.

Cryptography is often considered to be one of the harder challenge types
because many of the problems require deep specialization to understand.
However, we are not teaching deep specialization in this course, we are
teaching quick and dirty techniques to solve problems and find
resources.

There are a variety of common crypto problems such as:

1.  Ciphertext only
2.  Ciphertext + private key and algorithm
3.  Ciphertext and custom source code
4.  Ciphertext + public key and algorithm

For the most part, you will always get enough ciphertext for meaningful
statistics and for any advanced cryptography problem challenge makers
will let you know what the algorithm is because the ciphertext will all
be totally random. The only time you will get ciphertext only is for
very short, classical algorithms.

It is also unlikely that any problem is going to require extensive
password cracking or bruteforcing. If you find yourself needing extreme
computation, expect to have made a wrong turn somewhere.
