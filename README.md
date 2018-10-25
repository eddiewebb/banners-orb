# Banners Orb for CircleCI

Print messages, big.


## Summarize

Print a message big.

```
version: 2.1
orbs:
  banners: eddiewebb/banners@volatile

jobs:
  build:
    docker:
      - image: circleci/node:10
    working_directory: ~/repo
    steps:
      - banners/print:
          message: "Starting build"
      - run: #.... your code and stuff


```
creates
```
 ____  _             _   _               _           _ _     _ 
/ ___|| |_ __ _ _ __| |_(_)_ __   __ _  | |__  _   _(_) | __| |
\___ \| __/ _` | '__| __| | '_ \ / _` | | '_ \| | | | | |/ _` |
 ___) | || (_| | |  | |_| | | | | (_| | | |_) | |_| | | | (_| |
|____/ \__\__,_|_|   \__|_|_| |_|\__, | |_.__/ \__,_|_|_|\__,_|
                                 |___/                         
```

