# taailsScript
taailsScript, a custom scripting language. (and interpreter)

## Table of Contents
- [Features](#features)
- [VS Code Extension](#vs-code-extension)
- [Installation](#installation)
- [Usage](#usage)
- [Error Handling](#error-handling)
- [License](#license)

## Features
- Custom syntax and operations
- Error handling
- Mathematical operations

## VS Code Extension
I made a VS Code Extension that adds syntax highlighting to `.taails` files. The project is available [here](https://github.com/TaAils1440p/taailsScript-Code-Extension)

## Installation
To install the taailsScript interpreter, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone the repository or download the source code.
3. Navigate to the directory containing the interpreter.

```bash
git clone https://github.com/TaAils1440p/taailsScript.git
cd taailsScript
```

## Usage
To execute a taailsScript code file, use the shell.py script.

1. Create a `.taails` (or `.txt`) file
2. Write your script (or use the [exaple script](./example.taails))
3. Follow the steps down below

**Example of interactive use:**
```bash
python3 shell.py
```

In the custom shell, type:
```taails
RUN("your_file.taails")
```

## Error Handling
The interpreter includes a custom error handling system. Errors are defined with a start and end position, an error name, and details.

## License
taailsScript is released under the MIT License. See the [LICENSE](./LICENSE) file for more details.
