🔧 Purpose
Converts temperatures between Celsius, Fahrenheit, and Kelvin.

🧩 Functions

celsius_to_fahrenheit(c): °C → °F
fahrenheit_to_celsius(f): °F → °C
celsius_to_kelvin(c): °C → K
kelvin_to_celsius(k): K → °C
fahrenheit_to_kelvin(f): °F → K
kelvin_to_fahrenheit(k): K → °F
🏁 main() flow

Prints a menu of 6 conversion options.
Reads a numeric choice and a temperature value from user input.
Calls the chosen conversion function and prints the result formatted to 2 decimal places.
Prints "Invalid choice!" for out-of-range input.
✅ User-friendly bits

Clear menu and labels.
Results shown with degree symbols and 2 decimal precision.
⚠️ Potential improvements

Add input validation and exception handling (e.g., catch ValueError).
Support repeated conversions without restarting.
Use constants (e.g., K_OFFSET = 273.15) or a mapping for a cleaner structure.
🔍 Example
If you choose 1 and enter 0 → prints: "0.0 °C = 32.00 °F"
