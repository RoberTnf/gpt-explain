# GPT-commit

Simple script that uses ChatGPT to explain a command

## Installations

- Install `sgpt` from https://github.com/TheR1D/shell_gpt
- Then run `./gpt-explain` or add it to your `$PATH`

## Example usage

```
> ./gpt-explain "ls -lh > contents.txt"

This command lists the contents of the current directory using the 'ls' command. The '-lh' option makes the list human-readable and displays file sizes in a more understandable format. The '>' is a redirection operator that sends the output of the 'ls' command to a file named 'contents.txt' rather than displaying it on the screen.
```
