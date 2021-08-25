# go-lib-template

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/theflyingcodr/go-lib-template/Go?style=flat-square)
![GitHub](https://img.shields.io/github/license/theflyingcodr/go-lib-template?style=flat-square)
![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/theflyingcodr/go-lib-template?style=flat-square)
[![Report](https://goreportcard.com/badge/github.com/theflyingcodr/go-lib-template?style=flat&v=1)](https://goreportcard.com/report/github.com/theflyingcodr/go-lib-template)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/theflyingcodr/go-lib-template?style=flat-square)

A git template that can be used to bootstrap a go library, ie, something that isn't an executable.

This comes complete with git actions for:

* greetings  - welcome new contributors automatically
* build & release - to ensure your code is building before creating a release
* code quality - to scan for obvious issues

There is also a [Makefile](Makefile) with some handy common commands for running all tests, testing the releaser etc.

This will hopefully make a good starting point when you are looking to start a new go project.

## Getting started

* Create a new github repo
* Select this as the template
* Clone the repo
* run `go mod init github.com/youruser/yourporject`
* code code code

## Build pipeline

The go build will run on PRs and when pushed to master. When you tag master it will then run the go build and then create a release.

## Mergify

It also has a mergify config if you run that on your repos for auto merging etc.

Lets see if it works. Hmm
