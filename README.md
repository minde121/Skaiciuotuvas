Calculator_mgaidy
Calculator_mgaidy is a simple Python calculator class that supports basic arithmetic operations and maintains a history log. The calculator class provides methods for addition, subtraction, multiplication, division, exponentiation, and root operations. It also includes functionality to set precision, log operations, clear the history log, and reset the calculator memory.

Installation
You can install the Calculator_mgaidy package using pip:

bash
Copy code
pip install calculator-mgaidy
Usage
python
Copy code
from calculator_mgaidy import Calculator

# Create a calculator instance
calc = Calculator()

# Perform arithmetic operations
result_addition = calc.add(5)
result_subtraction = calc.subtract(3)
result_multiplication = calc.multiply(4)
result_division = calc.divide(2)
result_exponentiation = calc.power(3)
result_root = calc.root(2)

# Get the calculator memory and history log
memory_value = calc.memory
history_log = calc.logs

# Set precision
calc.set_precision(5)

# Clear history log
calc.clear_history_log()

# Reset memory
calc.reset_memory()
Constants
The calculator class includes constants for maximum and minimum allowed numbers in calculations and the maximum power level for exponentiation.

python
Copy code
MAX_NUMBER = Calculator.MAX_NUMBER
MIN_NUMBER = Calculator.MIN_NUMBER
MAX_POWER_LEVEL = Calculator.MAX_POWER_LEVEL
License
This project is licensed under the MIT License - see the LICENSE file for details.