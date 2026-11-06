# Eulers-Formula-Tracker

## Run the program

Open `index.html` in a web browser. There is no installation or internet connection required.

1. Enter the right-hand side of the differential equation `dy/dx = ...`. For example, `x + y`.
2. Enter the starting `x` and `y` values.
3. Fill in exactly two of step size (`Δx`), number of steps, and final `x`-value. The app calculates the remaining value. When a step size and final x-value are given, they must divide the interval into a whole number of steps.
4. Choose whether to show the calculated points and/or a plot, then select **Calculate endpoint**.

Expressions can use `x`, `y`, numbers, `pi`, `e`, parentheses, and `+`, `-`, `*`, `/`, or `^`. Multiplication must be explicit (`2*x`, not `2x`). Supported functions include `sin`, `cos`, `tan`, `asin`, `acos`, `atan`, `sqrt`, `abs`, `exp`, `log`, `log10`, `floor`, `ceil`, and `round`; put function arguments in parentheses, such as `sin(x)`. Trigonometric functions use radians.

The app supports up to 100,000 steps. Euler's Method produces an estimate, and smaller step sizes generally improve it.