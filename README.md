# minigrep

This is the hands-on walkthrough miniproject from Chapter 12 of [_The Rust Programming Language_](https://doc.rust-lang.org/book/ch12-00-an-io-project.html) book.

## synopsis

`minigrep` is a very simplified version of the famous [`grep`](https://en.wikipedia.org/wiki/Grep) Unix command.

`minigrep <substring> <filepath>`

It prints all lines that contain `substring` in the file pointed to by `filepath`.

## build and use

You need [Rust](https://www.rust-lang.org/tools/install) in order to build and install the `minigrep` CLI.

Run `cargo build` to build `minigrep`.

Then, run `target/debug/minigrep <substring> <filepath>`. 