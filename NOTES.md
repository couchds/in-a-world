# Notes on Go

`go.mod` - Specifies dependencies. *Indirect dependencies* are imported by direct dependencies but aren't listed in the
direct dependencies' respective go.mod files.

`go mod tidy` adds dependencies to your go.mod from the Go source.

`go.sum` lists checksums of all dependencies.

`go run .` builds (`go build`) and executes the given Go file(s).

When you're in package main, `go build` builds the package and stores the build in current directory.
