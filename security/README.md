# Practical Security

Do something to improve your personal security setup - if you’re not using a
password manager, set one up. If you’re doing that, then set up two factor for
some of your accounts. If you’re doing that, then set up proper SSH keypairs for
services that support it (e.g. GitHub). And you can keep going - set up a GPG
keypair, consider simple dedicated hardware for second factor, set up a trusted
computer/VM running only open source software, set up a "sandboxed" environment
for web browsing that doesn't save state, etc.

Use the practices and approaches we learned about this week - this means pick
a suitably long *passphrase* to protect your password manager, and think about
what your threat model is and what services you want to trust with what
information. Some general tips:

- You are a software developer, which means you're a high value target (you are
a potential attack vector to anyone who runs your code)
- Unless you're working on something controversial for the political regime you
reside in, the NSA/Mossad/KGB/MI5/etc. are probably not your adversaries
- The sorts of threats you *should* worry about - common criminals/organized
crime, botnets, malware, extortion (stealing your files, DDoS-ing your service)
- For deciding whether or not to trust a service, consider history, reputation,
and incentives, as well as what countries it operates in (which will impact the
laws it is subject to, both in terms of disclosure and potential damages)

Some resources/goals:
- [KeePass](https://en.wikipedia.org/wiki/KeePass) - open-source password manager
- [Alternatives to KeePass](https://alternativeto.net/software/keepass/) - cloud, desktop, etc., consider your personal security/convenience tradeoff
- [Two Factor Auth](https://twofactorauth.org/) - list of services that support 2 factor authentication
- [Connecting to GitHub with SSH](https://help.github.com/articles/connecting-to-github-with-ssh/) - more convenient (for command line) *and* secure than passwords
- [Adding GPG to your GitHub account](https://help.github.com/articles/generating-a-new-gpg-key/) - simple GPG setup that will let you sign commits
- [Creating the perfect GPG keypair](https://alexcabal.com/creating-the-perfect-gpg-keypair/) - more complicated, for those who want finer control
- [Keybase](https://keybase.io/) - a way to share/certify public keys (also offers encrypted chat, file storage, etc.)
- [Yubico](https://www.yubico.com/) - affordable hardware security devices for two-factor/crypto
- [How to install Ubuntu in VirtualBox](https://linus.nci.nih.gov/bdge/installUbuntu.html) - usable secure popular distribution of Linux
- [Kali Linux](https://www.kali.org/) - security-specific (penetration testing) distribution of Linux, includes VM images for download
- [Information about Sandboxes](https://en.wikipedia.org/wiki/Sandbox_(computer_security)) - general starting point for learning about sandboxes to contain an application

After you do some of the above, write 1-2 paragraphs summarizing what you did
(remember, a good security setup doesn't depend on security through obscurity,
so it should be safe to talk about it as long as you don't share actual
passwords/secrets). As a stretch goal, write a blog post about your security
setup describing what you’ve learned and tips you have for others.

Most of these things, I already have setup. 
I use Password Safe, which is installed both on my pc and on my phone
Almost all of my accounts (most importantly my credit card and bank) use two factor authentication
I setup SSH for GitHub a month or two ago
For work we use OpenVPN for communicating with the server while at home
A few weeks ago I converted an older PC to Linux because running it inside Windows10 was a bit slower than I liked
So I spent some time reading up on setting up OAuth in my applications