# Colorful Hello World
---
This repository contains a Python script that prints "Hello, World!" in various colors using the `colorama` library. It's a fun way to see how text can be colored in the terminal.

## Requirements

- Python 3.x
- `colorama` library

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mdriyadkhan585/Colorful-Hello-World
   cd Colorful-Hello-World
   ```

2. **Install the required library:**

   ```bash
   pip install colorama
   ```

## Usage

Run the Python script to see "Hello, World!" printed in different colors:

```bash
python hello_world.py
```

## Code Explanation

The script uses the `colorama` library to add color to the output. The `colorama` library must be initialized before using it.

### Example Code

```python
from colorama import Fore, Style, init

# Initialize colorama
init()

# Print a colorful "Hello, World!" message
print(Fore.RED + Style.BRIGHT + "Hello, World!" + Style.RESET_ALL)
print(Fore.GREEN + "Hello, World!" + Style.RESET_ALL)
print(Fore.BLUE + "Hello, World!" + Style.RESET_ALL)
```

- `Fore.RED`, `Fore.GREEN`, and `Fore.BLUE` are used to set the text color.
- `Style.BRIGHT` makes the text bright.
- `Style.RESET_ALL` resets the text color to default after each message.


## Author

Your Name - [RK Studio](https://github.com/mdriyadkhan585)
