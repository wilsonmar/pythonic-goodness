This repo contains Python utilities I developed to generate markdown files based on a _Porfolio.csv file.

Below are the Python language features used in the program source.

_portfolio_csv2md.py generates entire .md markdown files within a _products folder for use by Snipcart.

_portfolio_csv2txt2.py:

Underlines in file names are used to differentiate between the generator inputs and outputs.

0. Begin timer and end timer
0. Import library
1. File Path requires double slashes as escape characters
0. Obtain program name from program invocation arguments
1. Try/expect structure
2. Substitute a default value if not specified in program call arguments
0. Determine if file exists
1. Print current time
2. Concatenate text and numbers
3. Create (open) a file for writing 
0. Redirect STDOUT to a file
4. loop through an input CSV file
5. Reference specific columns
0. Line continuation character
1. Reset STDOUT back to original screen
6. Calculate elapsed time
0. Convert microseconds to seconds
0. Format floating point number
0. Calculate ratio of items per second.
