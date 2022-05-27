# Assembly

Learn Assembly For Fun

# How to Run

```bash
    nasm -f elf64 main.asm
    ld -s -o main main.o
    ./main
```
OR

```bash
    nasm -f elf64 main.s && ld main.o && ./a.out
```