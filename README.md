# Rust Gzip File Compressor

This Rust project provides a command-line utility to compress files using the Gzip format. It utilizes the `flate2` crate for compression.

## Features

- Compresses a source file into a Gzip format.
- Displays the sizes of the source and compressed files.
- Measures and outputs the elapsed time for the compression operation.

## Prerequisites

Make sure you have the following installed on your machine:

- [Rust](https://www.rust-lang.org/tools/install)
- Cargo (comes with Rust installation)

## Usage

To use the Gzip compressor, run the following command in your terminal:

```bash
cargo run <source_file> <target_file>
