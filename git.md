To use a `.gitignore` file, follow these steps:

1. Create a file called `.gitignore` in the root directory of your Git repository.
2. Add the files and directories that you want to ignore to the `.gitignore` file, one per line. For example, if you want to ignore all `.log` files, add `*.log` to the file. If you want to ignore a directory called `tmp`, add `tmp/` to the file.
3. Save the `.gitignore` file.
4. Commit the `.gitignore` file to your Git repository.
5. Git will now ignore the files and directories listed in the `.gitignore` file.

Here's an example `.gitignore` file:

```
# Ignore log files
*.log

# Ignore temporary directories
tmp/

# Ignore files and directories that start with a dot
.*

```

In this example, Git will ignore any files with the `.log` extension, any files or directories in the `tmp` directory, and any files or directories that start with a dot (such as `.idea` or `.vscode`).
