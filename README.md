<p align="center"><br><br>
<img src="https://github.com/linyows/dewy/raw/master/misc/dewy-logo.png" width="150"><br><br><br><br>
</p>

<p align="center">
<strong>DEWY</strong>: The application server for deployment with distributed polling.
</p>

<p align="center">
<a href="https://travis-ci.org/linyows/dewy"><img src="https://img.shields.io/travis/linyows/dewy.svg?style=for-the-badge" alt="travis"></a>
<a href="https://github.com/linyows/dewy/releases"><img src="http://img.shields.io/github/release/linyows/dewy.svg?style=for-the-badge" alt="GitHub Release"></a>
<a href="https://github.com/linyows/dewy/blob/master/LICENSE"><img src="http://img.shields.io/badge/license-MIT-blue.svg?style=for-the-badge" alt="MIT License"></a>
<a href="http://godoc.org/github.com/linyows/dewy"><img src="http://img.shields.io/badge/go-documentation-blue.svg?style=for-the-badge" alt="Go Documentation"></a>
</p><br><br>

Installation
------------

To install, use `go get`:

```sh
$ go get -d github.com/linyows/dewy
```

Usage
-----

When the application functions as a server:

```sh
$ dewy server --config /etc/dewy.d/your-application.conf
```

When the application and server are separated, or when the server is unnecessary:

```sh
$ dewy assets --config /etc/dewy.d/your-assets.conf
```

Contribution
------------

1. Fork ([https://github.com/linyows/dewy/fork](https://github.com/linyows/dewy/fork))
1. Create a feature branch
1. Commit your changes
1. Rebase your local changes against the master branch
1. Run test suite with the `go test ./...` command and confirm that it passes
1. Run `gofmt -s`
1. Create a new Pull Request

Author
------

[linyows](https://github.com/linyows)
