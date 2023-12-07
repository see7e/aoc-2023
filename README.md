# aoc-2023
My solutions for Advent of Code 2023


The first 7 problems (days 1-3 and the first part of day 4) are written in Python. Because I'm more confident as working with this language for a bigger timespan. But the runtime of a possible solution for the second part of day 4 would be too long. So as I was studying Go, I decided to give a try with this language. The result was:

```bash
$ python .\day_04.py
Score: 13
--- Part 1: Calibration:: 0.0038304 seconds ---
Score: 27845
--- Part 1: Official:: 0.1471868 seconds ---

$ go run .\day_04.go
Calibrate Score: 13
Calibrate Runtime: 0.0000000 seconds
Official Score: 27845
Official Runtime: 0.0010255 seconds 
```

The runtime of the Go solution for the first part is 143 times faster than the Python one. So I decided to continue with Go for the rest of the problems.

> [!TIP]
> To run Go code you can install the compiler from [this link](https://golang.org/dl/), and install the extension for VSCode.
> It's possilbe that some fail occurs when installing the `gopls` package, so you just need to run the command `go get golang.org/x/tools/gopls@latest` in the terminal.