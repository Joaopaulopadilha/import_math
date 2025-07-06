# JP Math Module

Mathematical functions and constants for the JP programming language.

## Installation

```bash
jp install math
```

## Usage

```jp
import math

// Basic functions
result = sqrt(16)        // 4.0
power = pow(2, 3)        // 8.0
sine = sin(PI / 2)       // 1.0
cosine = cos(0)          // 1.0
absolute = abs(-5)       // 5.0

// Rounding functions
up = ceil(3.2)           // 4.0
down = floor(3.8)        // 3.0

// Constants
circumference = 2 * PI * radius
exponential = pow(E, 2)
```

## Functions

| Function | Description | Example | Result |
|----------|-------------|---------|---------|
| `sqrt(x)` | Square root | `sqrt(16)` | `4.0` |
| `pow(base, exp)` | Power function | `pow(2, 3)` | `8.0` |
| `sin(x)` | Sine (radians) | `sin(PI/2)` | `1.0` |
| `cos(x)` | Cosine (radians) | `cos(0)` | `1.0` |
| `abs(x)` | Absolute value | `abs(-5)` | `5.0` |
| `ceil(x)` | Ceiling | `ceil(3.2)` | `4.0` |
| `floor(x)` | Floor | `floor(3.8)` | `3.0` |

## Constants

| Constant | Value | Description |
|----------|-------|-------------|
| `PI` | 3.14159... | Mathematical Pi |
| `E` | 2.71828... | Euler's number |

## Requirements

- C++ compiler with `<cmath>` support
- No external dependencies

## Examples

### Basic Calculator
```jp
import math

a = 5
b = 3

print("Addition:", a + b)
print("Power:", pow(a, b))
print("Square root:", sqrt(a * a + b * b))
```

### Trigonometry
```jp
import math

angle = PI / 4  // 45 degrees in radians
print("sin(45°):", sin(angle))
print("cos(45°):", cos(angle))
```

### Circle Calculations
```jp
import math

radius = 5
area = PI * pow(radius, 2)
circumference = 2 * PI * radius

print("Radius:", radius)
print("Area:", area)
print("Circumference:", circumference)
```

## License

MIT License - see LICENSE file for details.
