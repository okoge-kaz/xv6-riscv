# System Software, Fall 2022

Tokyo Institute of Technology

Lecture Site URL: https://titech-os.github.io/

## Overview

### Directory

```
xv6-riscv/
├── Dockerfile
├── LICENSE
├── Makefile
├── README.md
├── docker-compose.yaml
├── fs.img
├── kernel
├── mkfs
└── user
```
- `user/`

    User programs, such as `cat`, `echo`, `grep`, `init`, `kill`, `ln`, `ls`, `mkdir`, `rm`, `sh`, `stressfs`, `usertests`, `wc`, `zombie`.

- `kernel/`

## Environment

enter to xv6 environment

1. `docker compose up -d`
2. `docker container exec -it xv6-riscv /bin/bsh`
3. `make`
4. `make qemu`

quit from xv6 environment

1. type `Ctrl + A` and `X`

[Note] xv6 doesn't support `Ctrl + C` to quit.
