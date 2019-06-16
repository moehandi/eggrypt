<p align="center">
<a href="https://github.com/moehandi/eggrypt"><img src="https://img.shields.io/badge/Language-Go-blue.svg" alt="Language"></a>
<a href="https://goreportcard.com/report/github.com/moehandi/eggrypt"><img src="https://goreportcard.com/badge/github.com/moehandi/eggrypt" alt="GoReportCard"></a>
<a href="https://github.com/moehandi/eggrypt/blob/master/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License"></a>
<a href="https://github.com/moehandi/eggrypt/releases"><img src="https://img.shields.io/badge/Status-Beta-brightgreen.svg" alt="Status"></a>
</p>

## About eggrypt

eggrypt is a simple command line file encrypter for your daily needs.

eggrypt's goal is to be a simple tool to encrypt and password protect your files.

## Project Status

eggrypt is on beta. Pull Requests [are welcome](https://github.com/moehandi/eggrypt#social-coding)


## Features

- Uses [fcrypts](https://github.com/moehandi/fcrypts) libs
- Galois/Counter Mode (GCM) encryption (Extra secure, harder to bruteforce)
- Encrypts files so they can't be read unless the decrypter is used
- Protects your files with a password
- Fast encryption and decryption processes

## Installation

### Option 1: Go Get

```bash
$ go get github.com/moehandi/eggrypt
$ eggrypt
```

### Option 2: From source

```bash
$ git clone https://github.com/moehandi/eggrypt.git
$ cd eggrypt/
$ go get -d
$ go build *.go
```
## Usage

### Encryption

```bash
# Encrypts a file
$ eggrypt encrypt path/to/your/file
```

### Decryption

```bash
# Decrypts a file
$ eggrypt decrypt path/to/your/file
```

### Show help

```bash
$ eggrypt help
```

## Contributing

### Bug Reports & Feature Requests

Please use the [issue tracker](https://github.com/moehandi/eggrypt/issues) to report any bugs or file feature requests.

### Developing

PR's are welcome. To begin developing, do this:

```bash
$ git clone --recursive git@github.com:moehandi/eggrypt.git
$ cd eggrypt/
```

## Social Coding

1. Create an issue to discuss about your idea
2. [Fork it] (https://github.com/moehandi/eggrypt/fork)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create a new Pull Request

## Disclaimer

eggrypt is still on beta. 
We will not be held responsible for any file loses that may occur due to bugs or misuse of the program distributed here.
Always keep a backup in those cases.
