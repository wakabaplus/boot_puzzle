# A puzzle boot sector game (512 bytes)

**boot_puzzle** is a simple puzzle boot sector game written in Assembly.

## Requirement

To build:
- NASM

To run:
- QEMU or Bochs

## Run

To run with QEMU:
```shell
make qemu
```

To run with Bochs:
```shell
make debug
```

## How to play

Move the stone(`*`) to the Goal(`G`).
The player(`O`) can move a stone.
`X` is the wall.

To move the player, use **arrow keys**.
