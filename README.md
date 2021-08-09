Not even an alpha product. Just a mere prototype(s).

# First time running the demo:

1. Perform the trusted setup:

```console
$ cargo build --release
```

2. Set a wallet password. Note: you must set a password before using the wallet.

Open .config/darkfi/darkfid.toml and add a password to the 'Password' section.

3. Run the gateway daemon:

```console
$ cargo run --bin gatewayd -- -v
```

4. Run darkfid:

```console
$ cargo run --bin darkfid -- -v
```

5. Run cashierd:

```console
$ cargo run --bin cashierd -- -v
```

6. Initialize the wallet & Generate key pair:

```console
$ cargo run --bin drk -- -wk 
```

# Every time running the demo:

Run gateway daemon:

```console
$ cargo run --bin gatewayd -- -v
```

Run darkfid:

```console
$ cargo run --bin darkfid -- -v
```

Run cashierd:

```console
$ cargo run --bin cashierd -- -v
```

Show drk usage manual:

```console
$ cargo run --bin drk -- -help
```

# darkfid & drk configurations:

Darkfid and drk can be configured using the TOML files in the .config/darkfid directory. Make sure to recompile darkfid and drk after customizing the TOML.

# Go dark

Let's liberate people from the claws of big tech and create the democratic paradigm of technology.

Self-defense is integral to any organism's survival and growth.

Power to the minuteman.
