# Working with RIDE
### File Formats of Robot Framework

1. Plain text format:(.Robot and .txt Extension)
* Base for all supported Robot framework Data formats.
* Can be editing using normal text editor and IDE's
* Test Data is parsed Lined by Line
* In a single line Keyword and  Argumnets are separated By Separator

Most commonly used separator is Space Separed

Space Separated Format

Two or more space act as a separator between two different Data items

Minimum Space are two

2. TSV format (Tab separated Format)
* Files in the TSV format are typically edited in Sreadsheet
* Easy to generate programmatically

### Restructured Test format
* Easy to read plain test markup syntax used for documentation of python projects 
* Compiled to mostly HTML formats
* Test data is defined in code blocks

### HTML Format
* Not Supported anymore after Robot framework 3.1
* All test data converts to plain text format from html.