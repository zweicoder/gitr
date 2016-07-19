# GITR
Git that latest release! Right now it really just downloads the latest release by doing a regex search on all releases for the running OS. Useful for constantly updating [geth](https://github.com/ethereum/go-ethereum) for example.

## Usage
Put `gitr` somewhere on your path like `~/bin`

Get latest release from Github URL
`gitr https://github.com/zweicoder/gitr`

Or just the relative URL
`gitr zweicoder/gitr`

## TODO
- More extensive package management (e.g. version checks) ?