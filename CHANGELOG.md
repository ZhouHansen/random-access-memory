## 2018-08-30, Version 0.5.0
### Commits
- [[`3baa7c2d23`](https://github.com/datrs/random-access-memory/commits/3baa7c2d23dfa774ac5e1d2b38bbb171eaf95bc0)] (cargo-release) version 0.5.0 (Yoshua Wuyts)
- [[`300ead96ab`](https://github.com/datrs/random-access-memory/commits/300ead96ab4eab5b66f786f3b0562ddb29571d27)] Random access always open (#4) (Szabolcs Berecz)
- [[`db908834f8`](https://github.com/datrs/random-access-memory/commits/db908834f8e79dd8a8f98a22e1403da3ebf458da)] update changelog (Yoshua Wuyts)

### Stats
```diff
 .travis.yml         |  1 +-
 CHANGELOG.md        | 23 +++++++++++++++++-
 Cargo.toml          |  4 +--
 benches/sync.rs     |  2 +-
 src/lib.rs          | 74 ++++++++++++++++++++++++------------------------------
 tests/model.rs      |  2 +-
 tests/regression.rs |  8 ++----
 tests/test.rs       |  4 ++-
 8 files changed, 69 insertions(+), 49 deletions(-)
```


## 2018-08-23, Version 0.4.0
### Commits
- [[`7876a1a1ca`](https://github.com/datrs/random-access-memory/commits/7876a1a1ca10913a6126b767f4d07c3bae99dd8e)] (cargo-release) version 0.4.0 (Yoshua Wuyts)
- [[`cc83784775`](https://github.com/datrs/random-access-memory/commits/cc83784775a7cc737c97d514e88cdcb9ca2e718a)] upgrade random-access-storage (#3)

* upgrade random-access-storage

* cargo fmt (Yoshua Wuyts)
- [[`fae1a6509b`](https://github.com/datrs/random-access-memory/commits/fae1a6509b3c3825b3c063a627f64f85ab11cf40)] fix rustfmt in travis.yml (Yoshua Wuyts)
- [[`51c944434b`](https://github.com/datrs/random-access-memory/commits/51c944434b46c16ef7ba4028ac31ec10d6d64fe3)] fix benches (Yoshua Wuyts)
- [[`abfd505e04`](https://github.com/datrs/random-access-memory/commits/abfd505e049da526af068f475c1e8730e33238b9)] (cargo-release) start next development iteration 0.3.1-alpha.0 (Yoshua Wuyts)

### Stats
```diff
 .travis.yml         |  2 +-
 Cargo.toml          |  4 ++--
 benches/sync.rs     |  6 +++---
 src/lib.rs          | 23 ++++++++++++++++-------
 tests/regression.rs |  4 +---
 5 files changed, 23 insertions(+), 16 deletions(-)
```


