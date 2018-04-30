# CDT
This project aims to provide a very simple example of how to use CDT Plugin.

## Input
C/C++ code
## Output
Display function definition, and variable declaration in the given source code
## Example
Input: "int test(){int a=0;a++;}"

Output:
- A function definition: "int test(){int a=0;a++;}"
- A variable declaration: "int a=0"

## Set up
1. Add CDT project to Eclipse Mars, then configure libraries in /cdt
Right click to CDT project -> Build path -> Configura Build Path -> Libraries -> Add JARS -> Add all libraries in /cdt -> Apply
2. Run the function FunctionParser. Enjoy!
