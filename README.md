## How to run

### search, case-sensitive

```
cargo run -- to poem.txt > output.txt
```

### search, case-insensitive

```
IGNORE_CASE=1
cargo run -- to poem.txt > output.txt
```

### Unset environment variable

```
unset IGNORE_CASE
```
