Dorkcoin
=============

Setup
---------------------
Dork Core is a Dorkcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Dorkcoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Dork Core, visit [dorkcoin.org](https://dorkcoin.org).

Running
---------------------
The following are some helpful notes on how to run Dorkcoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/dorkcoin-qt` (GUI) or
- `bin/dorkcoind` (headless)

### Windows

Unpack the files into a directory, and then run dorkcoin-qt.exe.

### OS X

Drag Dorkcoin.app to your applications folder, and then run Dork Core.

### Need Help?

* Join comunity on [Discord server](https://discord.gg/jZYyJkzeWz).
* Ask for help on the BitcoinTalk in the [Dorkcoin Topic](https://bitcointalk.org/index.php?topic=5577864).

Building
---------------------
The following are developer notes on how to build Dorkcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Dorkcoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Join comunity on [Discord server](https://discord.gg/jZYyJkzeWz).
* Ask for help on the BitcoinTalk in the [Dorkcoin Topic](https://bitcointalk.org/index.php?topic=5577864).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
