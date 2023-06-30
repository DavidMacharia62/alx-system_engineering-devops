# LOOPS, CONDITIONS AND PARSING

In bash, loops allow you to execute a set of commands repeatedly. Here are some examples of loops in bash:

## For Loop:
bash
Copy code
for i in {1..5}; do
    echo "Iteration: $i"
done
This loop will iterate over the values 1 to 5 and print the iteration number.

## While Loop:
bash
Copy code
counter=1
while [ $counter -le 5 ]; do
    echo "Iteration: $counter"
    ((counter++))
done
This loop will execute as long as the condition $counter -le 5 (counter is less than or equal to 5) is true.

## Until Loop:
bash
Copy code
counter=1
until [ $counter -gt 5 ]; do
    echo "Iteration: $counter"
    ((counter++))
done
This loop will execute until the condition $counter -gt 5 (counter is greater than 5) becomes true.

## Variable assignment and arithmetic:

Variable Assignment: You can assign values to variables using the = operator. For example: variable="Hello, World!".
Arithmetic Operations: Bash supports arithmetic operations using the (( )) or $(( )) syntax. For example: result=$((2 + 3)).
Comparison operators:

-eq: Equal to.
-ne: Not equal to.
-gt: Greater than.
-lt: Less than.
-ge: Greater than or equal to.
-le: Less than or equal to.
Example: if [ $a -eq $b ]; then echo "Equal"; fi
File test operators:

-e: Checks if a file or directory exists.
-f: Checks if a path points to a regular file.
-d: Checks if a path points to a directory.
-r: Checks if a file has read permission.
-w: Checks if a file has write permission.
-x: Checks if a file has execute permission.
Example: if [ -f $file_path ]; then echo "File exists"; fi
To make your bash scripts more portable, consider the following tips:

Use POSIX-compliant syntax: Stick to the standard syntax and avoid using features specific to a particular shell.
Specify the interpreter: Begin your script with a shebang line (#!/bin/sh or #!/bin/bash) to ensure it runs with the correct interpreter.
Avoid assumptions about the system environment: Scripts should not rely on specific paths, dependencies, or configurations that may differ across systems.
Use portable commands: Prefer using commands available across different platforms rather than relying on platform-specific commands or options.
Test scripts on multiple systems: Verify that your script works as expected on different operating systems and shell environments.
By following these practices, you can increase the portability of your bash scripts across various systems and environments.
