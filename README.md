# Printerpret
A python program  that turns source code into a readable PDF.

## Structure
`./interpreters/` countains the files used by the program to check the syntax and to apply style accordint o that check.
* `language.csv` contains the regex that the code should match to be attributed a class
* `language.css` contains the style that is to be aplied to the class defined by the regex

Adding support for a new language should only require to crete a new CSV and .CSS files.