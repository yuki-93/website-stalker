Debian Releases
==========

 Debian always has at least
three releases in active maintenance:
>  stable

 ,
>  testing

 and
>  unstable

 .

[stable](https://www.debian.org/releases/stable/)

 The
>  stable

 distribution contains the latest officially released distribution of Debian.

 This is the production release of Debian, the one which we primarily recommend using.

 The current
>  stable

 distribution of Debian is version 12, codenamed  *bookworm*  .
It was initially released as version 12.0 on June 10th, 2023 and its latest update, version 12.6, was released on June 29th, 2024.

[testing](https://www.debian.org/releases/testing/)

 The
>  testing

 distribution contains packages that haven't been accepted into a
>  stable

 release yet, but they are in the queue for that. The main advantage of using this distribution is that it has more recent versions of software.

 See the [Debian FAQ](https://www.debian.org/doc/manuals/debian-faq/) for more information on [what is > testing](https://www.debian.org/doc/manuals/debian-faq/ftparchives#testing) and [how it becomes > stable](https://www.debian.org/doc/manuals/debian-faq/ftparchives#frozen) .

 The current
>  testing

 distribution is  *trixie*  .

[unstable](https://www.debian.org/releases/unstable/)

 The
>  unstable

 distribution is where active development of Debian occurs. Generally, this distribution is run by developers and those who like to live on the edge. It is recommended that users running unstable should subscribe to the debian-devel-announce mailing list to receive notifications of major changes, for example upgrades that may break.

 The
>  unstable

 distribution is always called  *sid*  .

 Release life cycle
----------

 Debian announces its new stable release on a regular basis. Users can expect 3 years of full support for each release and 2 years of extra LTS support.

 See [Debian Releases](https://wiki.debian.org/DebianReleases) Wiki page and [Debian LTS](https://wiki.debian.org/LTS) Wiki page for detailed information.

 Index of releases
----------

* [The next release of Debian is codenamed > trixie](https://www.debian.org/releases/trixie/) —
  >  testing

   — no release date has been set
* [Debian 12 ( > bookworm )](https://www.debian.org/releases/bookworm/) — current
  >  stable

   release
* [Debian 11 ( > bullseye )](https://www.debian.org/releases/bullseye/) — current
  >  oldstable

   release
* [Debian 10 ( > buster )](https://www.debian.org/releases/buster/) — current
  >  oldoldstable

   release, under [LTS support](https://wiki.debian.org/LTS)
* [Debian 9 ( > stretch )](https://www.debian.org/releases/stretch/) — archived release, under third-party paid [extended LTS support](https://wiki.debian.org/LTS/Extended)
* [Debian 8 ( > jessie )](https://www.debian.org/releases/jessie/) — archived release, under third-party paid [extended LTS support](https://wiki.debian.org/LTS/Extended)
* [Debian 7 ( > wheezy )](https://www.debian.org/releases/wheezy/) — obsolete stable release
* [Debian 6.0 ( > squeeze )](https://www.debian.org/releases/squeeze/) — obsolete stable release
* [Debian GNU/Linux 5.0 ( > lenny )](https://www.debian.org/releases/lenny/) — obsolete stable release
* [Debian GNU/Linux 4.0 ( > etch )](https://www.debian.org/releases/etch/) — obsolete stable release
* [Debian GNU/Linux 3.1 ( > sarge )](https://www.debian.org/releases/sarge/) — obsolete stable release
* [Debian GNU/Linux 3.0 ( > woody )](https://www.debian.org/releases/woody/) — obsolete stable release
* [Debian GNU/Linux 2.2 ( > potato )](https://www.debian.org/releases/potato/) — obsolete stable release
* [Debian GNU/Linux 2.1 ( > slink )](https://www.debian.org/releases/slink/) — obsolete stable release
* [Debian GNU/Linux 2.0 ( > hamm )](https://www.debian.org/releases/hamm/) — obsolete stable release

 The web pages for the obsolete Debian releases are kept intact, but
the releases themselves can only be found in a separate [archive](https://www.debian.org/distrib/archive) .

 See the [Debian FAQ](https://www.debian.org/doc/manuals/debian-faq/) for an explanation of [where all these codenames came from](https://www.debian.org/doc/manuals/debian-faq/ftparchives#sourceforcodenames) .

 Integrity of the data in the releases
----------

 Data integrity is granted by a digitally signed ` Release ` file. To ensure that all files in the release belong to it, checksums of
all ` Packages ` files are copied into the ` Release ` file.

 Digital signatures for this file are stored in the file ` Release.gpg ` , using the current version of the archive signing
key. For
>  stable

 and
>  oldstable

 an additional signature is
generated using an offline key specifically generated for a release
by a member of the [Stable Release Team](https://www.debian.org/intro/organization#release-team) .
