# GPG key

Gibhub has introduced a cool new function that allows creators to 'sign' their commits. This will show up as a green 'verified' on github.

Simply put, GPG, is an encrpytion software program.

There are a few simple steps to follow in order to get this up and running.

#Generate a new GPG

1. [Download and install](https://www.gnupg.org/download/) the GPG command line tools for your operating system.
2. Open Terminal and paste the text below to generate a GPG key pair:
   ```
   $ gpg --gen-key
   ```
3. Specify the kind of key you want or press `Enter` to accept the default `RSA and RSA`.
4. Enter the desired key size. *Maximum 4096 recommended*.
5. Enter the length of time you would like the key to be valid.
6. Veryify that your selections are correct.
7. Enter your user ID information.
8. Type a secure passphrase.
9. Enter `gpg --list-keys` to view existing GPG keys:
   ```
   $ gpg --list-keys
   ```
10. From the list, copy the eight character GPG key ID you'd like to use.
   ```
   gpg --list-keys
   /Users/hubot/.gnupg/pubring.gpg
   ------------------------------------
   pub   4096R/**==A8F99211==** 2016-04-05
   uid                  Hubot 
   sub   4096R/Z832QR89 2016-04-05
   ```
11. Paste the text below, substituting the GPG key ID you selected previously:
   ```
   $ gpg --armor --export **==A8F99211==**
   ```
12. Copy your GPG key, beginning with `-----BEGIN PGP PUBLIC KEY BLOCK-----` and ending with `-----END PGP PUBLIC KEY BLOCK-----`.

13. Add the GPG key to your GitHub account. See next section!
