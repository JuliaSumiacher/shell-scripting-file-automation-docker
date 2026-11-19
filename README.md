# Shell Scripting File Automation & Docker

A collection of Bash shell scripts organized around an interactive menu to automate file generation, processing, compression, and decompression, packaged with a `Dockerfile`.

## Project Structure

- `menu.sh` — Interactive menu entry point orchestrating the available shell scripts.
- `generar.sh` — Script for generating files.
- `procesar.sh` — Script for processing files.
- `comprimir.sh` — Script for compressing files.
- `descomprimir.sh` — Script for decompressing files.
- `dockerfile` — Container definition for running the shell scripts in a Docker environment.

## Usage

### Run Locally

Make the scripts executable and launch the interactive menu:

```bash
chmod +x *.sh
./menu.sh
