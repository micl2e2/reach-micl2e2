
# Table of Contents

1.  [(How-To) Encrypt Your Message For Me](#org1541c52)
2.  [(How-To) Import The Keys](#org27a45ee)



<a id="org1541c52"></a>

# (How-To) Encrypt Your Message For Me

Before encryption, you should ****Import The Keys****.

On Unix:

    echo 'my message' | gpg -aer micl2e2

The output should be like:

    -----BEGIN PGP MESSAGE-----
    
    .....................................
    .....................................
    -----END PGP MESSAGE-----

Now you can copy the output and send it to my Email address, which
can be found by `gpg --list-keys`.


<a id="org27a45ee"></a>

# (How-To) Import The Keys

Download the file `pgp-micl2e2.asc`, and run

    gpg --import pgp-micl2e2.asc

