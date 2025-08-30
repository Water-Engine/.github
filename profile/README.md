# The Water Engine

Welcome to the Water Engine! We are a small team of developers building a neural network powered chess engine.

## Mission
Our goal is to facilitate learning through doing, and to have fun and find success along the way. Iteration is paramount, failure is expected, recovery should be graceful.

### Philosophy
- Experiment freely: if you're on the fence about an implementation, just go for it!
- Keep it simple: focus on small, incremental improvements.
- Collaborate openly: share knowledge, review code, and support each other.

# Getting Started

```shell
git clone https://github.com/Water-Engine/water.git
cd water
make -j4 run
```

This will build and run the engine with a default configuration.

## Running the GUI (Cactus)

To play games or test the engine interactively:
```shell
git clone https://github.com/Water-Engine/water.git
cd water
make -j4 run
```

You can specify which engine plays white or black:

```shell
cargo run --release -- white path/to/water.exe black path/to/stockfish.exe
```

If paths are omitted or invalid, a normal human player is used.
