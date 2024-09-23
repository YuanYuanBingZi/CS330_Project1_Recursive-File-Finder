# Recursive File Finder

**Recursive File Finder** is a command-line utility written in C that recursively searches through directories and their subdirectories to locate files with a specific name. This tool is ideal for users who need to quickly find files within complex directory structures.

## Features

- Recursively searches through directories and subdirectories.
- Simple and easy-to-use command-line interface.
- Supports searching for files with exact names.
- Cross-platform compatibility (Linux, macOS, Windows).

## How It Works

The tool takes two arguments: the starting directory and the file name to search for. It will recursively traverse through all subdirectories from the starting directory, printing the full path of any matching files.

### Example Usage

```bash
./find_file . b.out
./project_dir/subdir/b.out
```