# Practice Algol 68 Genie

```bash
# Setup Docker
$ docker compose up -d

# Enter The Algol 68 Genie Container
$ docker exec -it algol sh
$$ pwd
/home/algol
$$ type a68g
a68g is /usr/local/bin/a68g

# Algol 68 Genie v2.8.4
$$ a68g --version
Algol 68 Genie 2.8.4
Copyright 2016 Marcel van der Veer <algol68g@xs4all.nl>.

This is free software covered by the GNU General Public License.
There is ABSOLUTELY NO WARRANTY for Algol 68 Genie;
not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details.

Please report bugs to Marcel van der Veer <algol68g@xs4all.nl>.

Compilation is supported.
Parallel-clause is supported.
Curses is not supported.
Regular expressions are supported.
TCP/IP is supported.
GNU libplot is not supported.
GNU Scientific Library is not supported.
PostgreSQL is not supported.

# Execute Files
$$ a68g ./hello-world-1.al
Hello World 1
$$ a68g ./hello-world-2.al
Hello World 2
$$ a68g ./hello-world-3.alg
Hello World 3

# Stop And Remove Environment
$ docker compose stop
$ docker compose rm
```


## References

- [Algol 68 Genie](https://jmvdveer.home.xs4all.nl/en.algol-68-genie.html)
- [Hello World in ALGOL 68 – The Renegade Coder](https://therenegadecoder.com/code/hello-world-in-algol-68/)
- [Dockerで開発環境 ALGOL68編 | 代表のブログ](https://blog.office-iwakiri.com/archives/development-839)
- [いろんな言語で “Hello World!” 〜1950年代 | 代表のブログ](https://blog.office-iwakiri.com/archives/development-763)
- [Yoshiya Hinosawa в Twitter: „hello world、"\n" みたいなエスケープシーケンスがなくて、new line というワードで改行を表現するのが面白い https://t.co/y3Tr59w7gc“ / Twitter](https://twitter.com/kt3k/status/1332621002778394624?lang=bg)
- [ALGOL - Wikipedia](https://ja.wikipedia.org/wiki/ALGOL)


## Links

- [Neo's World](https://neos21.net/)
