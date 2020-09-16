# Code Labs Tutorial Getting Started

Getting Started with Code Labs Formated Tutorial

## Description
- [googlecodelabs/tools](https://github.com/googlecodelabs/tools)

### Prerequisite
- Go
- Node.js v10+ and npm
- claat (open source command line tool maintained by Google)

#### Go
- [Download Site](https://golang.org/dl/)

#### Linux
```
$ wget https://golang.org/dl/go1.15.linux-amd64.tar.gz
$ sudo tar -C /usr/local -xzf  go1.15.linux-amd64.tar.gz
$ set --universal -x GOPATH $HOME/go
$ set --universal -x GOROOT /usr/local/go
$ vim ~/.config/fish/config.fish

$PATH:/usr/local/go/bin 
$PATH:$HOME/go/bin
```

#### Macbook
```
$ brew install go
$ export GOPATH=$HOME/Go
$ export GOROOT=/usr/local/opt/go/libexec
$ export PATH=$PATH:$GOPATH/bin
$ export PATH=$PATH:$GOROOT/bin
```

#### Node.js & npm
- `sudo apt update`
- `sudo apt install -y nodejs npm`

#### claat
- [claat](https://github.com/googlecodelabs/tools/tree/master/claat#install)
  - `go get -u -v -x github.com/googlecodelabs/tools/claat`

## Demo
### Claat Container
#### Pull Claat Container Image
```
$ docker pull shinyay/claat
```
## Features

- feature:1
- feature:2

## Requirement

## Usage

## Installation

## Licence

Released under the [MIT license](https://gist.githubusercontent.com/shinyay/56e54ee4c0e22db8211e05e70a63247e/raw/34c6fdd50d54aa8e23560c296424aeb61599aa71/LICENSE)

## Author

[shinyay](https://github.com/shinyay)
