# The Marion Filesystem

The Marion filesystem is a filesystem written in Python. It exposes a user configurable folder that integrates with a users Google Drive account. This folder encrypts anything placed within it before uploading it to Google Drive. This way, users don't have to worry about uploading sensitive data to the cloud and encryption is handled magically without much user interaction required.

## Requirements

In order to use Marion, the user will require a Google Drive account and have the GnuPG software version 2.0 or greater installed and working on their machine. Files may be encrypted either to the users PGP public key or symetrically using a provided password and AES256 bit encryption. This filesystem currently works on Linux only. Support for Microsoft Windows, BSD and OpenIndiana (OpenSolaris) is planned for the future.

## Is it open source?

Yes. You really can't trust code that you can't audit. Especially crypto code. Everything in Marion is open source and freely available under the BSD license.

## When will it be ready?

The beta version of Marion will be ready sometimes after the first of the year 2017. Right now, I'm the only developer working on it and I'm taking time to make sure I get everything stable and, most of all, secure. If you'd like to lend a hand, know Python, and have some free time, feel free to <a href="anthony@cajuntechie.org?Subject=Marion Filesystem">contact me and let me know</a>.
