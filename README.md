# Sort Files CLI

A powerful command-line tool that automatically organizes your files into categorized folders based on their file types. Keep your directories clean and organized with a simple command.

## Features

- 🚀 Automatically sorts files into predefined categories
- 📂 Creates organized folders for different file types
- 🔄 Ability to revert changes
- 👀 Preview changes before execution
- ⚡ Fast and efficient file organization

## Installation

Install globally using npm
npm install -g sort-files-cli

## Usage

### Basic Commands

```bash
# Sort current directory
sort-files

# Sort a specific directory
sort-files ~/Downloads

# Preview changes without actually moving files
sort-files --dry-run

# Revert files back to original location
sort-files --revert
```

### File Categories

The tool organizes files into the following categories:

#### 📸 Images

- Supported formats: jpg, jpeg, png, gif, bmp, svg, webp, ico, tiff, raw

#### 🎥 Videos

- Supported formats: mp4, mov, avi, mkv, wmv, flv, webm, m4v, mpeg, 3gp

#### 📄 Documents

- Supported formats: pdf, doc, docx, txt, rtf, odt, xls, xlsx, ppt, pptx, csv

#### 📦 Archives

- Supported formats: zip, rar, 7z, tar, gz, bz2, xz, iso

#### 🎵 Music

- Supported formats: mp3, wav, flac, m4a, aac, ogg, wma, aiff, alac, mid, midi

#### 💻 Code

- Supported formats: js, py, html, css, ts, json, md, jsx, tsx, c, cpp, java, go

#### ⚙️ Executables

- Supported formats: exe, dmg, pkg, app, sh, bin

#### 📚 E-books

- Supported formats: epub, mobi, azw3, fb2

#### 🔡 Fonts

- Supported formats: ttf, otf, woff, woff2, eot

### Options

```bash
-d, --dry-run    Preview changes without moving files
-r, --revert     Revert files to their original location
-h, --help       Display help information
-V, --version    Display version number
```

## Examples

```bash
# Sort Downloads folder with preview
sort-files ~/Downloads --dry-run

# Sort Desktop folder
sort-files ~/Desktop

# Revert changes in Downloads folder
sort-files ~/Downloads --revert
```

## How It Works

1. **Scanning**: The tool scans the specified directory for files
2. **Categorizing**: Files are categorized based on their extensions
3. **Organization**: Files are moved to their respective category folders
4. **Feedback**: Provides real-time feedback about the sorting process

## Important Notes

- Files without extensions are skipped
- Files in subdirectories are not affected
- Category folders are created only when needed
- Original file names are preserved
- Use `--dry-run` to preview changes before execution

## Error Handling

- Provides clear error messages
- Safely handles file conflicts
- Prevents accidental file overwrites
- Validates directory permissions

## Author

Tochukwu Nweke

## License

MIT

## Issues and Contributions

Found a bug or want to contribute? Please visit:
[GitHub Repository](https://github.com/nwekeKent/sort-file-cli)
EOL
