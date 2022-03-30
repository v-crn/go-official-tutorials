# Create a Go module

1. [Tutorial: Create a Go module - The Go Programming Language](https://go.dev/doc/tutorial/create-module)
2. [Call your code from another module - The Go Programming Language](https://go.dev/doc/tutorial/call-module-code)

## 2022-03-30

期待：

```console
$ go run .
Hi, Gladys. Welcome!
```

実際：

```console
$ go run .
# example.com/hello
./hello.go:4:2: imported and not used: "example.com/greetings" as greetigns
./hello.go:10:13: undefined: greetings
```

原因と解決策が不明。
