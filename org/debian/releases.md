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
It was initially released as version 12.0 on June 10th, 2023 and its latest update, version 12.7, was released on August 31st, 2024.

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

 Debian announces its new stable release on a regular basis. The Debian release life cycle encompasses five years: the first three years of full support followed by two years of Long Term Support (LTS).

 See [Debian Releases](https://wiki.debian.org/DebianReleases) Wiki page and [Debian LTS](https://wiki.debian.org/LTS) Wiki page for detailed information.

 Index of releases
----------

| Version|                        Code Name                       | Release Date| End of Life (EOL)|  EOL LTS  |  EOL ELTS |                                                 Status                                                 |
|--------|--------------------------------------------------------|-------------|------------------|-----------|-----------|--------------------------------------------------------------------------------------------------------|
|   14   |                          Forky                         |     TBA     |        TBA       |    TBA    |    TBA    |                                           Codename announced                                           |
|   13   |   [Trixie](https://www.debian.org/releases/trixie/)  |     TBA     |        TBA       |    TBA    |    TBA    |                          >  testing<br/><br/> — no release date has been set                           |
|   12   | [Bookworm](https://www.debian.org/releases/bookworm/)|  2023-06-10 |    2026-06-10    | 2028-06-30| 2033-06-30|                                 Current<br/>>  stable<br/><br/> release                                |
|   11   | [Bullseye](https://www.debian.org/releases/bullseye/)|  2021-08-14 |    2024-08-14    | 2026-08-31| 2031-06-30|                               Current<br/>>  oldstable<br/><br/> release                               |
|   10   |   [Buster](https://www.debian.org/releases/buster/)  |  2019-07-06 |    2022-09-10    | 2024-06-30| 2029-06-30| Archived release, under third-party paid [extended LTS support](https://wiki.debian.org/LTS/Extended)|
|    9   |  [Stretch](https://www.debian.org/releases/stretch/) |  2017-06-17 |    2020-07-18    | 2022-07-01| 2027-06-30| Archived release, under third-party paid [extended LTS support](https://wiki.debian.org/LTS/Extended)|
|    8   |   [Jessie](https://www.debian.org/releases/jessie/)  |  2015-04-25 |    2018-06-17    | 2020-06-30| 2025-06-30| Archived release, under third-party paid [extended LTS support](https://wiki.debian.org/LTS/Extended)|

 Older releases:

* [Debian 7.0 ( > wheezy )](https://www.debian.org/releases/wheezy/) — obsolete stable release
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
