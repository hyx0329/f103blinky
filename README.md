# f103blinky

Rust Embedded project (STM32F1) template for VSCode

Using BlackMagic Probe as debugger, have to install __Native Debug__ first.
The extension can be installed by pressing `Ctrl+Shift+P` and run `ext install webfreak.debug`

The blinky code becomes simpler as the HAL crate evolving.

## How to use

- Update the package name in `Cargo.toml`.
- Update the path to executable in `.vscode/launch.json`.
- Update the linker script if necessary.
- Or just copy the files suitable for a new project and then apply the modifications.

## Useful links

- [GDB cheat sheet](https://gabriellesc.github.io/teaching/resources/GDB-cheat-sheet.pdf)
