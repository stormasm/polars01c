
This document reads from the bottom of this page to the top...

### polars01c

* polars-io

### polars01b

* polars-ops
* polars-time

### polars01a

* polars-arrow
* polars-core
* polars-utils

After refactoring polars01 I decided to break out the architecture into
a crates directory similar to the way
[nushell](https://github.com/nushell/nushell) 
is designed.

```rust
[workspace]
members = [
  "crates/polars-arrow",
  "crates/polars-core",
  "crates/polars-utils",
]
```

### polars01

A fork of
[polars](https://github.com/pola-rs/polars)

with just these 3 crates

* polars-arrow
* polars-core
* polars-util

at this
[branchpoint](https://github.com/pola-rs/polars/commit/eb42b99d82ed2a64e2817381b54491e0cb0fcf3b)

### polars

My fork of polars will always be aligned with this breakout architecture...

* [polars](https://github.com/stormasm/polars)
