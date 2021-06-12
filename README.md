# polkadots
## CVE-2021-3560 Local PrivEsc Exploit

Affected Distributions:
* RHEL 8
* Fedora 21
* Debian testing (Bullseye)
* Ubuntu 20.04

## Usage

    ./polkadots -a [Account] -n [Account name] -h [Password hash] -i [iterations]
		     Generate hashed password with: openssl passwd -6 password@123

    Defaults:
      -a boris
	    -n Boris Ivanovich Grishenko
	    -h $6$cGKhfu9znRnOQV1h$2j/3WKyqTcCaftP1PGhW8Pghj2qV5j8zwy1gHrt9eILUE6WKeWVCTa9QgkskIfwVXpjVI.TuX2D.rEkbwKubi/
	    -i 20
  
#### Discovered By: Kevin Backhouse
#### Source: https://github.blog/2021-06-10-privilege-escalation-polkit-root-on-linux-with-bug/
