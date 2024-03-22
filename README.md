# KAMOS - Kamil Operating System

## Description

KAMOS (Kamil Operating System) is a lightweight operating system designed for x86 architecture. It features basic commands and a file system based on CHS (Cylinder-Head-Sector). The system allows users to interact with it through a command-line interface.

## Features

- Basic commands for system management.
- File system based on CHS addressing.
- Interpreter "KB2" like Basic

## Usage

After installation, you can use KAMOS by following these steps:
1. Boot your computer with KAMOS.
2. Access the command-line interface.
3. Use the available commands to interact with the system.

## Commands

- `SAVE`: Opens a text editor where users can write text. Pressing the 'esc' key saves the text in the sector where the SAVE program was launched.
- `LOAD`: Allows you to read saved text on a sector.
- `GOTO`: Allows you to move to another sector, heads or cylinder. the program will ask you to enter the parameters and the number of readable sectors at once.
- `INFO`: This command displays information from the system and its updates.
- `VER`: This command displays informations about version system.
- `COPY`: This command allows you to copy the contents of the sector and paste it using the `PASTE` command.
- `HEX` and `ASCII`: These commands display characters and translate them to a given purpose in the case of HEX to hexadecimal and ASCII to decimal.
- `CLEAR`: Cleans consoles.
- `HEXDUMP`: Allows you to view the content in hexadecimal.
- `SHUTDOWN`: Shutdown system.
- `KB2`: Starts the KB2 interpreter in which you can interpret programs contained in the current sector we are on. If you don't know how to use `KB2`, there is a syntax learning program called `TRANING`.
- `LIST` Lists all sectors starting with #.
- `XGUI` Emits a graphic system based on subtitle coloring.
- `CACHE` This command allows you to see what is in the cache.

## Contributing

Contributions to KAMOS are welcome! If you'd like to contribute, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes.
- Submit a pull request.

## License

This project is licensed under the "All Rights Reserved".

## Author

KAMOS was created by Kamil Malicki. You can contact the author at kamilpusiu2008@gmail.com.
