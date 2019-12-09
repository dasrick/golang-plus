[![Docker Pulls][dockerpull-image]][dockerpull-url]
[![Docker Cloud Automated][dockerautomated-image]][dockerautomated-url]
[![Docker Cloud Build][dockercloudbuild-image]][dockercloudbuild-url]
[![License][license-image]][license-url]

***

# Golang plus

Official docker image of golang extended with some useful tools like

* dep
* golint
* zip/unzip
* golangci-lint (golang >= 1.13.5)

Currently all images based on `golang:<version>-stretch` image

## Tags

* shared tags: `1.13`, `latest` => `1.13.5`
* `1.13.0` ... `1.13.5`
* shared tags: `1.12` => `1.12.14`
* `1.12.0` ... `1.12.14`
* shared tags: `1.11` => `1.11.13`

## Usage

Example: `docker pull dasrick/golang-plus:1.13.3`

## Release History

A detailed history of golang can be found [here](https://golang.org/doc/devel/release.html). 
* [go.1.13 minor](https://golang.org/doc/devel/release.html#go1.13.minor)
* [go.1.12 minor](https://golang.org/doc/devel/release.html#go1.12.minor)
* [go.1.11 minor](https://golang.org/doc/devel/release.html#go1.11.minor)

***

[dockerpull-image]: https://img.shields.io/docker/pulls/dasrick/golang-plus.svg?style=flat-square
[dockerpull-url]: https://hub.docker.com/r/dasrick/golang-plus

[dockerautomated-image]: https://img.shields.io/docker/cloud/automated/dasrick/golang-plus?style=flat-square
[dockerautomated-url]: https://hub.docker.com/r/dasrick/golang-plus

[dockercloudbuild-image]: https://img.shields.io/docker/cloud/build/dasrick/golang-plus?style=flat-square
[dockercloudbuild-url]: https://hub.docker.com/r/dasrick/golang-plus

[license-image]: https://img.shields.io/github/license/dasrick/golang-plus.svg?style=flat-square
[license-url]: https://github.com/dasrick/golang-plus/blob/master/LICENSE
