# linux-smart-enumeration
Linux enumeration tools for pentesting and CTFs

This shell script will show relevant information about the security of the local Linux system, helping to escalate privileges.

It has 3 levels of verbosity so you can control how much information you see.

In the default level you should see the highly important security flaws in the system. The level `1` (`./lse.sh -l1`) shows
interesting information that should help you to privesc. The level `2` (`./lse.sh -l2`) will just dump all the information it
gathers about the system.


## Usage

`wget "https://raw.githubusercontent.com/diego-treitos/linux-smart-enumeration/master/lse.sh " -O - | /bin/bash`

`curl -s -L "https://github.com/diego-treitos/linux-smart-enumeration/releases/latest/download/lse.sh" | /bin/bash`
