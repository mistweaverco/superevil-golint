# Super Evil Golang Linter
A super evil linter for Golang.

## Requirements

- Linux or MacOS
- [Golang][golang]

## Installation

Install using one of the following locations:

- https://git.superevilmegaco.com/golang/superevil-golint
- https://github.com/stroeerdigitalpublishing/superevil-golint
- https://github.com/superevilmegaco/superevil-golint

## Usage

Switch to the root of your project directory and run the following command

```bash
go lint
```

## Passing checks

To pass the *linting* rules, your code has to pass the following checks:

- [gofmt][gofmt]
- [golint][golint]
- have at least 90% code coverage

## Dependencies

These dependencies are automatically resolved when you install the
*Super Evil Golang Linter*.

- [gofmt][gofmt]
- [gomega][gomega]
- [goblin][goblin]
- [golint][golint]



[gofmt]: https://golang.org/cmd/gofmt/
[gomega]: https://github.com/onsi/gomega
[goblin]: https://github.com/franela/goblin
[golint]: https://godoc.org/golang.org/x/lint/golint
[golang]: https://golang.org/

