# Empty-Deps

A tiny shell script for build rust dependencies
that assumes they all use rust-empty or provide
a similar interface. Use at your own risk.

## Usage

Assuming you have a `deps` folder, just run `sh empty-deps`
to build all of your deps and place all of their dylibs and
rlibs in your `target/lib` folder in the top directory.

That is all.

## License

MI
