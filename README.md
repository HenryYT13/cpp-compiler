# cpp-compile

A simple bash utility to compile and run a single C++ file, then clean up the binary — all in one command.

## Usage

```bash
cpp-compile <file>
```

Compiles `<file>.cpp`, runs the resulting binary, and automatically removes it after execution.

### Example

```bash
cpp-compile main
```

This runs:
```bash
g++ main.cpp -o main && ./main && rm main
```

## Install

```bash
git clone https://github.com/HenryYT13/cpp-compiler.git
chmod +x cpp-compile
sudo mv cpp-compile /bin/
cd .. & rm cpp-compile
```
