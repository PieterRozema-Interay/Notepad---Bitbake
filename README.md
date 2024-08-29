# BitBake Language Support for Notepad++

## Overview

This repository provides syntax highlighting and language support for BitBake files in Notepad++. It supports the following file types:
- `.bb` (BitBake recipes)
- `.bbappend` (BitBake recipe append files)
- `.bbclass` (BitBake class files)

## Features

- Syntax highlighting for `.bb`, `.bbappend`, and `.bbclass` files
- Enhanced readability with color-coded keywords, variables, and functions
- Support for BitBake-specific constructs and syntax

## Installation

To use this language support in Notepad++, follow these steps:

1. **Download the Files:**
   - Clone this repository or download the files from the repository.

2. **Install the User Defined Language (UDL) File:**
   - Open Notepad++.
   - Go to `Language` > `Define your language...`.
   - Click `Import...` and select the `bitbake.xml` file from this repository.
   - Click `Save As` and name the language (e.g., "BitBake").

3. **Apply the Language:**
   - Open a BitBake file (`.bb`, `.bbappend`, `.bbclass`) in Notepad++.
   - Go to `Language` in the menu bar.
   - Select the language you defined (e.g., "BitBake") from the list.

## Configuration

The syntax highlighting is configured in the `bitbake.xml` file. You can customize the language definitions and color schemes by editing this XML file.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
