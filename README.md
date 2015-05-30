SimulOS
=======

***PROJECT IS DISCONTINUED***

An "Operating System" simulation written in bash shell script.

Style information
-----------------

Comments:

```bash
# Category:

# Information.
```

Functions:

```bash
return="" # For functions with return values.

# Description of the function.
# return-value name [--options] required-arguments [optional-arguments] (Optional)
function name() {
code
return=return-value
}

function caller() {
name required-arguments
dostuffwith $return
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
