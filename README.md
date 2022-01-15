# NOTE
Since circa 2010 it's been said throughout the internet that there's an ipv6 version of this tool.

This is not true, I was the one who took the idea of making an ipv6 compatible version of this tool.

However, this never happened, because back then Nelson Brito released t50 publicly and it became the de-facto packet injector tool for this kind of purpose.

Of course, you could feed pcap files to tcpreplay, but still...

The source code in this repository is the solely unique version of this tool, in it's original form.

# geminid
Also known as g3m.c - geminid is an oldschool packet injector



Compiling

     Default (same as -DLINUX)
     % gcc geminid.c -o geminid

     With password file option:
     % gcc -DF_PASS geminid.c -o geminid

     With Linux htons() and BANNER_CKSUM 54018
     % gcc -DLINUX geminid.c -o geminid

     With Solaris x86 BANNER_CKSUM 54016
     % gcc -DSUNX86 geminid.c -o geminid

     With FreeBSD BANNER_CKSUM 54016
     % gcc -DFREEBSD geminid.c -o geminid

     With Sun SPARC BANNER_CKSUM 723
     % gcc -DSUNSPARC geminid.c -o geminid

by LIVE

