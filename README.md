# K&R C Exercises

Personal solutions and extended implementations for exercises from  
"The C Programming Language (2nd Edition)" by Kernighan & Ritchie.

> This repository contains only my original code.  
> Exercise descriptions are NOT included due to copyright.

---

## About

This repository documents my study of C programming using K&R’s 
classic book as a foundation.

---

## Environment

- Compiler: `gcc` / `clang`
- C Standard: `C99`
- Warning Flags: `-Wall -Wextra -Werror`
- OS: macOS / Linux
- Build Tool: Makefile

---

## Repository Structure

```
.
├── chapter-1/
│   ├── ex1-01.c
│   ├── ex1-02.c
│
├── chapter-2/
│   ├── ex2-01.c
│   ├── ex2-02.c
│
├── Makefile
└── README.md
```

### Naming Convention

- `exX-YY.c` → Chapter X, Exercise YY

---

## Build & Run

Compile a single exercise:

```bash
gcc -std=c99 -Wall -Wextra chapter-1/ex1-01.c -o ex1-01
./ex1-01
```

Build entire project:

```bash
make
```

Run tests:

```bash
make test
```

Clean build files:

```bash
make clean
```

---

## Copyright Notice

This repository does NOT include:

- Exercise descriptions
- Scanned pages
- Direct excerpts from the book

Only original solution code written by me is included.

---

## License

All source code in this repository is licensed under the MIT License.
