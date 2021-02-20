# Passerine Fibonacci
A simple program that calculates the first few fibonacci numbers.

Written in [Passerine 0.9.0](https://github.com/vrtbl/passerine), a nice little programming language I made.

Here's the core program:

```passerine
fib = n -> if ((n == 0.0) or (n == 1.0)) {
    1.0
} else {
    fib (n - 1.0) + fib (n - 2.0)
}
```

You can install passerine and run this program as follows:

```shell
sh <(curl -sSf https://www.passerine.io/install.sh)
git clone https://github.com/slightknack/passerine-fibonacci.git
cd passerine-fibonacci
aspen run
```
