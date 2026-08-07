**PROJECT UNDER CONSTRUCTION**
# CTRL-TUI
CTRL-TUI is a TUI (Terminal User Interface) client write from scratch in C++ using terminal [ANSI escape sequence](https://en.wikipedia.org/wiki/ANSI_escape_code)

## INSTALLATION : 
### REQUIREMENT
- glibc (adding proper musl support later)
- GNU Make
- A linux system

### STEP
1. Clone the project and go in the project folder
```sh
git clone https://github.com/Gun8hoot/CTRL-TUI.git && cd CTRL-TUI
```
2. Compile the Project
```sh
make
```
3. Launch the project
```sh
./ctrl-tui
```

## USAGE : 
- Q / CTRL+C = close the TUI
- ↑ / ↓ = Move from one position
- ← / → = Move from two position

## THE IDEA
![main](./assets/main_menu.png)
![search](./assets/search_menu.png)

## KNOWN BUGS
1. Drawing thread not properly killed when sending SIGINT signal
