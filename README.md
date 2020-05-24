# interpreter
A follow along and modification/expansion of the interpreter presented by Thorsten Ball in the book "Writing an Interpreter in Go". Most coding conventions have been adopted from Ball's book.

# usage
The interpreter package includes a repl for testing the pieces of the interpreter. If you want to run the repl, you can do the following.
1. Create a main package and main file inside of the package.
2. Import the repl, fmt, and os packages
3. Call the Start function of the repl by doing repl.Start(os.Stdin, os.Stdout) inside the main function
