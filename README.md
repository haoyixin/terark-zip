# Introduction

Terark-Core is the foundation of TerarkDB and TerarkKV, it contains a series of algorithms that support storage engine development:

- Index algorithms
  - cspp trie
  - composite uint index
  - scgt
  - ...
- Value store algorithms
  - DictZipBlobStore
  - EntropyZipBlobStore
  - MixedLenBlobStore
  - ...

## Complile
1. Install libaio-dev first if you dont have it yet
2. `build.sh` will do the rest work


## Unit Tests
Terark-Core contains a set of serious test cases under `./tests`, you can run them all by using `run_all.sh` to make sure your modification doesn't break previous code logic.

## Integration
If you want to use Terark-Core in you own application, simple include the headers and link terark-core's three libraries.

Terark-Core's API detail:

TODO
