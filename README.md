# Minishell
This repo provides, as the name already says, a minishell.  
Functionalities:
- have a working history
- redirections and here-document
- piping
- environment variables ($ followed by characters) expand to their values
- getting exit status
- ctrl-C ctrl-D ctrl-\ work like in bash

Tested on macOS Monterey.

## Installation

#### 1) Install the readline library
```
brew install readline
```

#### 2) Clone this repository 
```
git clone git@github.com:JL1709/minishell.git
```

#### 3) Execute Makfile
```
cd Minishell
make
```

#### 4)  Run program
```
./minishell
```
This project was developed together with <a href="https://github.com/vytkuklys">vytkuklys</a>
