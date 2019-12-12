# Mandelbrot Plotter with Rust

A simple Mandelbrot plotter written in Rust following the example in [Programming Rust](https://www.amazon.com/Programming-Rust-Fast-Systems-Development/dp/1491927283).

## Slide Deck

This project discussed at the [Desert Rust](https://rust.azdevs.org/) meetup. The [slide deck](docs/mandelbrot.pdf) is included in this repo in the `/docs` folder.

## Usage

1. Build and run the program:

```
cargo run -- mandel.png <IMAGE_WIDTHx<IMAGE_HEIGHT> <UPPER_RIGHT_Z> <LOWER_LEFT_Z>
```

e.g.:

```
cargo run -- mandel.png 4000x3000 -1.20,0.35 -1,0.20
```
