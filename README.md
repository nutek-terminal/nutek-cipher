# nutek-cipher

Encrypt and decrypt files and text.

## setup

```shell
cargo install nutek-cipher
```

## usage

```shell
Usage: nutek-cipher [OPTIONS]

Options:
  -e, --encrypt                        encrypt
  -d, --decrypt                        decrypt
  -i, --input <INPUT>                  set input file
  -o, --output <OUTPUT>                set output file
      --stdin <STDIN>                  from stdin
      --password-file <PASSWORD_FILE>  password from file
      --stdout                         print result to stdout
  -h, --help                           Print help
  -V, --version                        Print version
```

## cipher in use

This program uses *AES CBC* cipher with *32 bit* key. It's enough for home use.

## roadmap

* hash password and derive _asymetric_ key
* include _initialization vector_

## crypto gurus

Probably my vocabulary is wrong, but I want to supply a working copy of encryption/decryption tool;

I'm opened to pull requests correcting my mistakes, although for now there is nothing wrong with the program itself.
