[![Build Status](https://travis-ci.org/gnormal/gnorm.svg?branch=master)](https://travis-ci.org/gnormal/gnorm)
<h1 align="center">GNORM</h1>

<p align="center"><img src="https://user-images.githubusercontent.com/3185864/29906052-5fd530a2-8de0-11e7-964e-1112fb152ee1.png" /></p>
<p align="center">GNORM is Not an ORM.</p>

## About

Gnorm is a database-first code generator that generates boilerplate that matches
your database's schema.  

Gnorm uses templates you control, so that you can make the output look exactly
how you want it to look.  It can be used to generate type-safe database queries
that are faster than a traditional ORM.  It can also be used to create a REST or
RPC API that exposes the data in your database.

## Documentation

[https://gnorm.org](https://gnorm.org)

## Installing

Gnorm has no dependencies, just download and run the executable for your
operating system.  See our [latest release](https://github.com/gnormal/gnorm/releases/latest).

## Building

__Note:__ Gnorm uses a go vanity url.  To install with go get, run 

```
go get gnorm.org/gnorm
```

However, using go get to install will mean that `gnorm version` doesn't report
the correct data. 

For best results, use the go "makefile" in the root of the repo, which will do
all the build-time magic:

```
go run make.go
```

If you want to git clone instead (which should work fine since we vendor all
dependencies), make sure you git clone into `$GOPATH/src/gnorm.org/gnorm`.

## Discussion 

If you have questions about Gnorm or want to hack on it, meet the devs on the
`#gnorm` channel of [gopher slack](https://gophers.slack.com/).

There's also the `#gnorm-dev` channel which has github integrations showing the
work going on.

## Contributing

See CONTRIBUTING.md