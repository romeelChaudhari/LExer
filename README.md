# Lexer
 Modify the Lexer
You will be extending the Lexer to be able to process four new tokens, as well as to improve the output of the Lexer.
1. The current implementation of Lexer reads a hardcoded file. Lexer must be updated to allow input via a filename provided as a command line argument:
java lexer/Lexer simple.x (Please note that you do not need to run the project via command line, instead run it through NetBeans, adding the commands line arguments to the project as explained in class).
2. Our compiler must be updated to accommodate 8 additional tokens: >, >=, ||, &&, void, float, double, and **. The tokens file must be updated, and TokenSetup must be ran to re-generate the Tokens and TokenTypes classes.
3. The Token class must be updated to include the line number that a token was found (for subsequent error reporting, etc.).
4. Lexer output must be updated for readability, and to include the line number from the Token (Note that the
initial debug text that shows the file information has been removed!) (Note that the initial debug text that shows
  the file information has been removed!).
READLINE:   program {boolean j int i
program   left: 0      right: 6       line: 1
{         left: 8 .    right: 8       line: 1
boolean   left: 9 .    right: 15      line: 1
j         left: 17 .   right: 17      line: 1
int       left: 19 .   right: 21      line: 1
i         left: 23 .   right: 23      line: 1
READLINE:     int factorial(int n) {
