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

```bash
# Using the superevilmegaco.com Git mirror
go get git.superevilmegaco.com/golang/superevil-golint

# Using the repository from stroeerdigitalpublishing on Github
go get github.com/stroeerdigitalpublishing/superevil-golint

# Using the repository from superevilmegaco on Github
go get github.com/superevilmegaco/superevil-golint
```

### Custom mirrors

You can always mirror one of the locations found above and use your own
location then.

Just fork this repository and you're good to go.

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

