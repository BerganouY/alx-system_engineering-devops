# Shell Variables and Expansions

This project contains scripts that demonstrate various aspects of shell variables, expansions, and scripting in Bash.

## Script Descriptions

### 0-alias
Creates an alias named `ls` with value `rm *`.  
**Warning:** This is a dangerous alias that will delete files when `ls` is run.

### 1-hello_you
Prints "hello user" where user is the current Linux user.

### 2-path
Adds `/action` to the `PATH` environment variable (last position).

### 3-paths
Counts the number of directories in the `PATH` environment variable.

### 4-global_variables
Lists all environment variables.

### 5-local_variables
Lists all local variables, environment variables, and functions.

### 6-create_local_variable
Creates a new local variable named `BEST` with value `School`.

### 7-create_global_variable
Creates a new global variable named `BEST` with value `School`.

### 8-true_knowledge
Prints the result of adding 128 to the value stored in `TRUEKNOWLEDGE`.

### 9-divide_and_rule
Prints the result of `POWER` divided by `DIVIDE`.

### 10-love_exponent_breath
Displays the result of `BREATH` to the power `LOVE`.

### 11-binary_to_decimal
Converts a number from base 2 (stored in `BINARY`) to base 10.

### 12-combinations
Prints all possible two-letter combinations (a-z) except `oo`.

### 13-print_float
Prints a number (from `NUM`) with two decimal places.

### 100-decimal_to_hexadecimal
Converts a number from base 10 (in `DECIMAL`) to base 16.

### 101-rot13
Encodes/decodes text using ROT13 encryption.

### 102-odd
Prints every other line from input, starting with first line.

### 103-water_and_stir
Adds numbers stored in `WATER` (base-water) and `STIR` (base-stir), outputting in base-bestchol.

## Requirements
- All scripts are exactly 2 lines long
- First line must be `#!/bin/bash`
- No use of `&&`, `||`, `;`, `bc`, `sed`, or `awk`
- All files must be executable
- Tested on Ubuntu 20.04 LTS

## Usage
1. Clone the repository
2. Make scripts executable: `chmod u+x *.sh`
3. Run scripts: `./script_name` or source them: `. ./script_name`

## Skills Learned
- Shell initialization files
- Local vs global variables
- Shell expansions
- Arithmetic operations
- Base conversions
- Environment variables
- Shell scripting best practices

## Author
Berganou Yassine

## License
This project is part of the ALX School program.