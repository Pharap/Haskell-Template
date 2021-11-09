# Haskell-Template

A template Haskell program for use as a basis in VSCode.

The included scripts make it easy to do `clean && build && run` from the command line and the `settings.json` in `.vscode` will hide the `.hi` and `.o` files from the file browser (along with some other files and folders that may potentially be annoying).

## Files

### Main.hs

A basic 'hello world' program to serve as the basis of any program.

### build.bat

Calls `@ghc Main.hs` to build the program.

### clean.bat

Recursively deletes all `.hi`, `.o` and `.exe` files.

### run.bat

Calls `@Main` to run the program.

### settings.json

Hides `.hi`, `.o` and other files and folders from the file browser.
