# SimplyComplex

## What is it?

SimplyComplex is as web application designed for interactive visualization of complex functions.
You can check its live version [here](https://wqferr.github.io/SimplyComplex/).

## How does it work?

Firstly, this project is coded almost entirely in Lua, using the Fengari VM for JavaScript.

Paths drawn on the input canvas are warped according to a user defined function.
The resulting paths are drawn on the output canvas with the same color. Path widths
are also multiplied by the absolute value of the derivative at their starting point.
This lets you see regions of rapid change in the function.

Complex numbers implementation used is [imagine](https://github.com/wqferr/imagine), also by me.
The function and derivative are calculated and evaluated using the
[SymDiff](https://github.com/wqferr/SymDiff) library in the `compat-imagine` branch, also also by me.

## License

SimplyComplex is distributed under GPLv3.
