
# Polyominoes

Generates the free, one-sided, and fixed [polyominoes](https://en.wikipedia.org/wiki/Polyomino)
in Haskell.

## Running

Built with GHC 7.10.3. To run, clone the repository and run

```
$ runhaskell App.hs
```

## Sample Output

```
$ runhaskell App.hs
Generate polyominoes of length: 4
Polyominoes of type {free, one-sided, fixed}: one-sided
■ □ □ □
■ □ □ □
■ □ □ □
■ □ □ □

□ □ □ □
■ □ □ □
■ □ □ □
■ ■ □ □

□ □ □ □
□ ■ □ □
□ ■ □ □
■ ■ □ □

□ □ □ □
■ □ □ □
■ ■ □ □
■ □ □ □

□ □ □ □
□ □ □ □
■ ■ □ □
■ ■ □ □

□ □ □ □
■ □ □ □
■ ■ □ □
□ ■ □ □

□ □ □ □
□ □ □ □
■ ■ □ □
□ ■ ■ □
```