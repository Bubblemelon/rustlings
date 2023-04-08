# 🍉🫧 rustlings 🦀

Learning Rust through this popularly recommended resource.

See the [original README](https://github.com/rust-lang/rustlings/blob/main/README.md) for this for this forked repo.

## Local Install & Usage

<a href="https://github.com/rust-lang/rustlings/fork"><kbd>Fork</kbd></a> `rustlings`, then:

```bash
git clone https://github.com/Bubblemelon/rustlings.git
```

Set up upstream link to keep repository up-to-date:

```bash
git remote add upstream git@github.com:rust-lang/rustlings.git

git fetch upstream 
```

Update Rust installer and install `rustlings`:

```bash
rustup update

cd rustlings

cargo install rustlings
```

For list of `rustling` commands:

```bash
rustlings --help
```

Learn from compile and runtime error:
```
rustlings watch
```
> Reruns `rustlings verify` when files edited.

To uninstall:

```bash
cargo uninstall rustlings
```