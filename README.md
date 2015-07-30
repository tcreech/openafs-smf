# openafs-smf
Somewhat generic [SMF][smf] for [Illumos][illumos] [OpenAFS][openafs] clients and servers, adapted from phalenor's for Penn State/BX.

Ultimately, I hope to have a [pkgsrc][pkgsrc] port which automatically generates these. For now, the client SMF port works nicely with the [openafs port][tcreechopenafsport] in my [personal pkgsrc][tcreechpkgsrc]. (The server SMF is still untouched from phalenor's.)

[smf]: http://www.illumos.org/man/5/smf
[illumos]: http://illumos.org
[openafs]: http://openafs.org
[phalenor]: http://github.com/phalenor
[pkgsrc]: http://pkgsrc.org
[tcreechpkgsrc]: http://github.com/tcreech/pkgsrc/
[tcreechopenafsport]: http://github.com/tcreech/pkgsrc/tree/trunk/filesystems/openafs
