# CS1: Lab 10

## Setup
1. Update the contents of *ID.txt* with your identifier (school email **without @school.edu**).
2. Write pseudocode for your program in *PSEUDO.txt*.

## How to Run Your Program
* [**WINDOWS**]
   - In VSCode, press the play button in the top right corner (it should appear when you open a `.cpp` file). Your program should compile and run.
   - Alternatively, open a terminal. Type `.\make.bat` and press return. Your program should compile and run.
* [**MAC/LINUX**]
   - Open a Terminal. Type `make` and press return. Your program should compile and run.

## Assignment Specification
### String Cheese
* Implement this program in `main.cpp`.
* The program initially prompts the user for a string.
   - This string may include spaces
   - The input should be stored as a C-String
   - The input string will have a maximum of 128 characters
* The program should display a menu with several options:
   - **Inverse String** - changes lowercase characters to uppercase and vice versa
   - **Reverse String** - reverses the order of characters in the string
   - **To Uppercase** - converts all alphabetic characters to uppercase
   - **Count Consonants** - displays the number of consonant (non-vowel) characters in the string
   - **Count Words** - displays the number of words in the string
   - **Change String** - update the string 
   - **Print** - displays the string
   - **Quit** - terminate the program
* After an option is selected, the corresponding operation should be performed and the program should print a short status message.
* Note that Inverse String, Reverse String, To Uppercase, and Change String *do not output anything to the terminal*; they are directly modifying the string.
* If the user selects an invalid menu option, they should be continuously prompted until a valid option is entered. Otherwise, the user may manipulate the string until they quit the program.

### Other Requirements
* The starter code provides exactly one C-String called *storage*. No other C-Strings should be declared in your program.
* No additional libraries should be included other than those provided in the starter code. 
* Your program logic must be organized into functions; you will be graded on code cleanliness and design.

#### Example
```
Enter a string: bun paTTy ketchup must4rD p1ckLes oni0n Lettuce chee5e t0Mato bun

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
5) Change String
6) Print
7) Quit
Enter a choice: 99
Invalid choice, please try again: 1
String has been inverted.

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 7
BUN PAttY KETCHUP MUST4Rd P1CKlES ONI0N lETTUCE CHEE5E T0mATO BUN

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 2
String has been reversed.

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 7
NUB OTAm0T E5EEHC ECUTTEl N0INO SElKC1P dR4TSUM PUHCTEK YttAP NUB

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 3
String has been converted to uppercase.

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 7
NUB OTAM0T E5EEHC ECUTTEL N0INO SELKC1P DR4TSUM PUHCTEK YTTAP NUB


String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 4
String has 34 consonants.

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 5
String has 10 words.

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 6
Enter a string: chum

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 7
chum

String Menu
—------------------
1) Inverse String
2) Reverse String
3) To Uppercase
4) Count Consonants
5) Count Words
6) Change String
7) Print
8) Quit
Enter a choice: 8

```

## Submission
1. Remember to *commit* and *push* your changes to this repository.
