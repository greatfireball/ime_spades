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
Specific tags are used for different SPAdes release.

### master
- [![](https://images.microbadger.com/badges/version/greatfireball/ime_spades:master.svg)](https://microbadger.com/images/greatfireball/ime_spades:master "Get your own version badge on microbadger.com")
- [![](https://images.microbadger.com/badges/commit/greatfireball/ime_spades:master.svg)](https://microbadger.com/images/greatfireball/ime_spades:master "Get your own commit badge on microbadger.com")
- [![](https://images.microbadger.com/badges/image/greatfireball/ime_spades:master.svg)](https://microbadger.com/images/greatfireball/ime_spades:master "Get your own image badge on microbadger.com")

### develop
- [![](https://images.microbadger.com/badges/version/greatfireball/ime_spades:develop.svg)](https://microbadger.com/images/greatfireball/ime_spades:develop "Get your own version badge on microbadger.com")
- [![](https://images.microbadger.com/badges/commit/greatfireball/ime_spades:develop.svg)](https://microbadger.com/images/greatfireball/ime_spades:develop "Get your own commit badge on microbadger.com")
- [![](https://images.microbadger.com/badges/image/greatfireball/ime_spades:develop.svg)](https://microbadger.com/images/greatfireball/ime_spades:develop "Get your own image badge on microbadger.com")

### release 3.13.0
- [![](https://images.microbadger.com/badges/version/greatfireball/ime_spades:3.13.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.13.0 "Get your own version badge on microbadger.com")
- [![](https://images.microbadger.com/badges/commit/greatfireball/ime_spades:3.13.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.13.0 "Get your own commit badge on microbadger.com")
- [![](https://images.microbadger.com/badges/image/greatfireball/ime_spades:3.13.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.13.0 "Get your own image badge on microbadger.com")

### release 3.12.0
- [![](https://images.microbadger.com/badges/version/greatfireball/ime_spades:3.12.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.12.0 "Get your own version badge on microbadger.com")
- [![](https://images.microbadger.com/badges/commit/greatfireball/ime_spades:3.12.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.12.0 "Get your own commit badge on microbadger.com")
- [![](https://images.microbadger.com/badges/image/greatfireball/ime_spades:3.12.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.12.0 "Get your own image badge on microbadger.com")

### release 3.11.1
- [![](https://images.microbadger.com/badges/version/greatfireball/ime_spades:3.11.1.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.11.1 "Get your own version badge on microbadger.com")
- [![](https://images.microbadger.com/badges/commit/greatfireball/ime_spades:3.11.1.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.11.1 "Get your own commit badge on microbadger.com")
- [![](https://images.microbadger.com/badges/image/greatfireball/ime_spades:3.11.1.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.11.1 "Get your own image badge on microbadger.com")

### release 3.11.0
- [![](https://images.microbadger.com/badges/version/greatfireball/ime_spades:3.11.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.11.0 "Get your own version badge on microbadger.com")
- [![](https://images.microbadger.com/badges/commit/greatfireball/ime_spades:3.11.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.11.0 "Get your own commit badge on microbadger.com")
- [![](https://images.microbadger.com/badges/image/greatfireball/ime_spades:3.11.0.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.11.0 "Get your own image badge on microbadger.com")

### release 3.10.1
- [![](https://images.microbadger.com/badges/version/greatfireball/ime_spades:3.10.1.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.10.1 "Get your own version badge on microbadger.com")
- [![](https://images.microbadger.com/badges/commit/greatfireball/ime_spades:3.10.1.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.10.1 "Get your own commit badge on microbadger.com")
- [![](https://images.microbadger.com/badges/image/greatfireball/ime_spades:3.10.1.svg)](https://microbadger.com/images/greatfireball/ime_spades:3.10.1 "Get your own image badge on microbadger.com")
