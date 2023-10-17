# MINESWEEPER!

MINESWEEPER! is my project of hardware system at HUST, fall 2023. In this project, I developed a simplified minesweeper game, which supports:
- A 16x16 game board with 40 mines.
- Random generation of mine layouts.
- Ensuring that the first clicked cell will not be a mine.
- Marking flags on the cells freely.
- Running on a self-made RISC-V CPU.
- Running on x86 machines via SDL2.

## Requirements
```bash
paru -S clang lld cmake
```

## Build
```bash
cmake -B build
cd build && make
```

## TODO
- [ ] Add support of mouse for x86 machines.
- [ ] Add a window containing some information about the game.
- [ ] Add a message bar to guide players.