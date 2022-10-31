# sssa-golang

An implementation of Shamir's Secret Sharing Algorithm in Go  

## Usage
Note: this library is for a pure implementation of SSS in Go;

usage:

    sssa.Create(minimum int, shares int, raw string) - creates a set of shares

    sssa.Combine(shares []string) - combines shares into secret

For more detailed documentation, check out docs/sssa.md.

