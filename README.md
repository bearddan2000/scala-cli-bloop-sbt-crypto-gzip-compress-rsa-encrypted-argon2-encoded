# scala-cli-bloop-sbt-crypto-gzip-compress-rsa-encrypted-argon2-encoded

## Description
Encrypt and decrypt password with RSA.
To compress the encrypted text gzip was used.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt

## Docker stack
- FROM hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [Correct way to convert string to byte Array](https://stackoverflow.com/questions/140131/convert-a-string-representation-of-a-hex-dump-to-a-byte-array-using-java)
- [RSA Code](https://www.geeksforgeeks.org/asymmetric-encryption-cryptography-in-java/)
- [GZIPCompression](https://stackoverflow.com/questions/16351668/compression-and-decompression-of-string-data-in-java)
