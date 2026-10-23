# Fibonacci Sequence Generator

A C console program (`fb1.c`) that asks for a number of terms and prints that many Fibonacci numbers, starting with 0 and 1. It uses a recursive function.

## Build and run

```sh
gcc fb1.c -o fibonacci
./fibonacci
```

On Windows, run `fibonacci.exe`.

## Notes

The program rejects nonpositive term counts, but does not validate failed input. Recursive recalculation becomes slow for large counts, and the `int` result eventually overflows.
