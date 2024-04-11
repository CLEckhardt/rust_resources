# Rust Resources

> This is a work in progress. Have a suggestion? Open an issue!

## Why Rust?

There are a lot of reasons you might want to learn and use Rust. I've found
they vary across people and organizations, and they change over time and with
more experience. I've linked some discussions of "why Rust?" below; however,
given this simple question forms a expansive and nuanced topic, these are
simply a few perspectives.

These focus more on "why Rust?" in a professional context. On a personal level,
"why Rust?" is really up to you. Talking to other folks on the Rust-learning
journey can help bump your inspiration and motivation. But if you are
struggling to come up with a reason besides "all the cool kids are doing it and
I don't want to be left out," don't sweat it and go spend your time on
something you enjoy more. Rust will still be here if you want to come back to
it.

* [Why Rust in
  production?](https://corrode.dev/why-rust/#reasons-for-using-rust-in-production)
* [Fast development in
  Rust](https://blog.sdf.com/i/142481359/fearless-refactors)
* [Error handling in Rust](https://barretts.club/posts/go-errors/)

## New? Start here

[Install Rust](https://www.rust-lang.org/tools/install) here.

This list is sorted by how broadly helpful I think these resources could be,
i.e. resources that more folks find helpful are listed higher up. We all learn
differently and have different backgrounds, so use whichever work for you.

I'd recommend starting at the top of this list - if something isn't working for
you, move on to the next one. Or pick the one that sounds the most interesting
(though I'd recommend starting with a comprehensive resource).

_This is just my take. Have a suggestion? Open an issue!_

1. [Rust book](https://doc.rust-lang.org/book/) [comprehensive]
2. [Rust by example](https://doc.rust-lang.org/rust-by-example/)
   [comprehensive]
3. [Interactive Rust book](https://rust-book.cs.brown.edu/) [comprehensive,
   interactive]
4. [Rustlings](https://github.com/rust-lang/rustlings) [interactive]
5. [Rust development classes](https://rust-classes.com/preface)
6. [Video Rust
   book](https://www.youtube.com/watch?v=OX9HJsJUDxA&list=PLai5B987bZ9CoVR-QEIN9foz4QCJ0H2Y8)
   [comprehensive]
7. [Rust
   Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/intro.html)
8. [Learning Rust with far too many linked
   lists](https://rust-unofficial.github.io/too-many-lists/)
9. [Command Line Apps in Rust](https://rust-cli.github.io/book/index.html)

### Development tools

One great thing about Rust is that it is easy to use without an IDE. The
tooling provided with the language works out-of-the-box and enables you to be
productive quickly.

The two main tools that come with Rust are
[`rustup`](https://rust-lang.github.io/rustup/) and
[`cargo`](https://doc.rust-lang.org/cargo/). `rustup` manages your Rust
toolchain and versions, plus many other tools. `cargo` is Rust's build system,
package manager, and a simple interface to all sorts of great features and
tools. It's worth taking a look at the [cargo
book](https://doc.rust-lang.org/cargo/), but also note that cargo can be
extended via a wide range of
[plugins](https://crates.io/categories/development-tools::cargo-plugins) and
stand-alone tools you can install via `cargo install <tool>`. Building,
checking, testing, benchmarking, linting, formatting, dependency analysis,
auditing, fuzzing, and more all happen through simple `cargo` commands.

The most common IDEs/editors for Rust are VSCode, vi/vim/neovim, or a JetBrains
IDE (Rust Rover or another IDE with a Rust plugin).
[rust-analyzer](https://rust-analyzer.github.io/) is the official Rust language
server and is easy to install.

Rust has a default formatter,
[`rustfmt`](https://github.com/rust-lang/rustfmt). Unlike other languages,
there isn't a popular alternative - it is widely used and generally considered
"the" formatter. `rustfmt` runs on the entire project via the `cargo fmt`
command, but you can configure your editor to run it on the current file only.
`rustfmt` is conveniently installed and updated automatically via `rustup`.

[`clippy`](https://doc.rust-lang.org/nightly/clippy/) is Rust's default linter
and is also automatically managed by `rustup`. It has preset levels to choose
from and is highly customizable. Using `clippy` can be a great way to learn how
to write idiomatic Rust code!

### Miscellaneous

* [This Week in Rust](https://this-week-in-rust.org/) - The official unofficial
  newsletter
* Find Rust communities on discord, redit, meetup,
  the-platform-formerly-known-as-twitter, etc. - lots of resources

## Intermediate/advanced

These resources aren't in a particular order, but delve into the more advanced
features or aspects of Rust.

* [The Rustonomicon](https://doc.rust-lang.org/nomicon/) - Unsafe Rust
* [Little book of Rust macros](https://danielkeep.github.io/tlborm/book/README.html)
* [The Rust Reference](https://doc.rust-lang.org/reference/index.html) - The
  technical description of the Rust language
* [RFC book](https://rust-lang.github.io/rfcs/) - Active and historical Rust
  RFCs; useful for better understanding specific features and design decisions
* [Jon Gjengset's channel](https://www.youtube.com/@jonhoo)
* [Rust for Rustaceans](https://nostarch.com/rust-rustaceans)
* [Rust atomics and locks](https://marabos.nl/atomics/) - Low-level concurrency in Rust
* [withoutboats blog](https://without.boats/)
