# Shell Scripting File Automation & Docker

A collection of Bash shell scripts organized around an interactive menu to automate file generation, processing, compression, and decompression, packaged with a `Dockerfile`.

## Project Structure

- `menu.sh` — Interactive menu entry point orchestrating the available shell scripts[cite: 21].
- `generar.sh` — Script for generating files[cite: 21].
- `procesar.sh` — Script for processing files[cite: 21].
- `comprimir.sh` — Script for compressing files[cite: 21].
- `descomprimir.sh` — Script for decompressing files[cite: 21].
- `dockerfile` — Container definition for running the shell scripts in a Docker environment[cite: 21].

## Usage

### Run Locally

Make the scripts executable and launch the interactive menu[cite: 21]:

```bash
chmod +x *.sh
./menu.sh
