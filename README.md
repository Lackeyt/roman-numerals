#  _Roman Numeral Generator_

#### _Converts user number to roman numerals_
##### __Created:__ 6/11/2020
##### __Last Updated:__ 6/11/2020 
##### By _**Tyson Lackey, Kate Skorija, Erich Richter**_  

## Description

_Takes a user inputed number between 1-3999. Based on the behavior logic bellow, it converts the number to roman numeral notation and returns the text_

## Behaviors

| Spec| Example input | Example Output
| ----------- | ----------- | ----------- |
| An entered number is converted into it's corresponding symbol | "10" | "X" |
| the entered number will equal the sum of all symbols | "60" | "LX" |
| Symbols are displayed largest to smallest | "1111" | "MCXI" |
| if the sum of all symbols requires more than 3 consecutive cases of the same symbol, use subtraction to reach the sum of consecutive values. | "4" | "IV" |
| ones, tens, hundreds, and thousands need to evaulate separately. | "99" | "XCIX" (not: "IC") |
| If a non-integer is entered, return an error | "325hello" | "enter a number between 1-3999" |
| Entered numbers must be between 1-3999 | "4000" | "enter a number between 1-3999" |

## Setup/Installation Requirements

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open by downloading:
1. Internet Browser
2. Code editor like VScode to view the codebase

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open by downloading:

1. Download this repository onto your computer
2. Double click index.html to open it in your web browser

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open via Bash/GitBash:

1. Clone this repository onto your computer:
    "git clone https://github.com/Lackeyt/roman-numerals"
2. Navigate into the "roman-numeral" directory in Visual Studio Code or preferred text editor:
3. Open the project
    "code ."
3. Open index.html in your browser:
    "open index.html"


## Known Bugs

* Does not currently error handle non-integer inputs
* Does not currently error handle integers entered that are not between 1-3999
* Currently does not contain custom CSS styling and minimal bootstrap defaults

## Support and contact details

* Discord: TysonL#4409
* Email: lackeyt90@gmail.com


## Technologies Used

* Visual Studio Code
* HTML
* CSS
* Bootstrap
* Javascript
* JQuery

## Resources:

* 

### License

Copyright (c) 2020 **_Tyson Lackey_**

This software is licensed under the MIT license.