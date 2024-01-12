# Gzip Compression Utility 📦

A simple command-line utility written in Rust for compressing files using Gzip compression.

## Usage 🚀

Ensure you have Rust installed, and then run the following command to build the project:

```bash
cargo build --release
```

After building, you can use the utility as follows:

```bash
./gzip-compressor source_file target_file
```

Replace `source_file` with the path to the file you want to compress and `target_file` with the desired output path.

## Example 🌐

```bash
./gzip-compressor input.txt compressed_output.gz
```

## Requirements 🛠️

- Rust (https://www.rust-lang.org/tools/install)

## How it Works 🤖

1. Reads the contents of the source file.
2. Compresses the data using Gzip compression.
3. Writes the compressed data to the specified target file.

## Performance Metrics ⏱️

The utility provides information about the source and target file lengths, as well as the elapsed time during compression.

```bash
Source len: <source_file_length>
Target len: <compressed_output_length>
Elapsed: <elapsed_time>
```

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute, report issues, or suggest improvements! 🤝
