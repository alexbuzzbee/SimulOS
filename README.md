SimulOS
=======

An "Operating System" simulation writen in bash shell script.

Style information
-----------------

Comments:

```bash
# Category:

# Information.
```

Functions:

```bash
name="" # For functions with return values.

# Description of the function.
# return-value name [--options] required-arguments [optional-arguments] (Optional)
function name() {
code
name=return-value
}

function caller() {
name required-arguments
dostuffwith $name
}
```

Variables:

```bash
name="" # Define the variable.
name=value # Set the variable.

OR

name=value # Define the variable and set it's initial value (use at the top of functions and files).

$name # Use the variable.
```
