# ime_spades
Docker container for SPAdes assembler

## Usage

The docker image runs `spades.py` as entry point and `--test` as command.
Therefore, if running the container, the test assembly will be performed.

```
docker run --rm -greatfireball/ime_spades --version
```

Just provide all required parameters via command line.
Default working directory is `/data`.
Therefore, input data should be mounted using `/data` volume.

## Releases

The master branch contains a rolling release.

### master
- [![](https://images.microbadger.com/badges/version/greatfireball/ime_spades:master.svg)](https://microbadger.com/images/greatfireball/ime_spades:master "Get your own version badge on microbadger.com")
- [![](https://images.microbadger.com/badges/commit/greatfireball/ime_spades:master.svg)](https://microbadger.com/images/greatfireball/ime_spades:master "Get your own commit badge on microbadger.com")
- [![](https://images.microbadger.com/badges/image/greatfireball/ime_spades:master.svg)](https://microbadger.com/images/greatfireball/ime_spades:master "Get your own image badge on microbadger.com")
