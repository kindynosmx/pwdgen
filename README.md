# Easy to remember and readable password generator

This code is based on and ported to Rust from the password generator created by Christian Haensel and modified by Josh Hartman, which can be found at https://www.warpconduit.net/password-generator/.

## Requirements

- [Rust](https://www.rust-lang.org/tools/install)

## Install

1. Clone the repository

```
git clone https://github.com/eabz/password-generator && cd password-generator
```

2. Build the program

```
cargo build --release
```

3. Run the generator

```
./target/release/generator
```

## Program flags

| Flag            | Default | Purpose                                 |
| --------------- | :-----: | --------------------------------------- |
| -p, --passwords |   10    | Amount of passwords to generate.        |
| -l, --length    |   14    | Amount of characters for each password. |
