# Delimiters :rocket: 

Characters used to delimit between small parts called tokens. 

They exist in 3 forms
- Single delimiters <space> is a delimiter,';' is a delimiter
- symetric delimiters : '< >', ' " " ', ' ( ) '
- Asymetric paired delimiters : \n, #

# Tokens

Characters or a sequence of them.

They can be **keywords**, those are tokens predefined by C. 

# Statements :rocket: 
Statements are the building blocks of a program. They form a complete unit of computational logic, like the human cell in biology.

### Types 

We have a variety of statements : 

- Simple statement : 'printf(...);' or 'return 0;' are simple  statements
	- Function call statement : printf(...)  
	- Return statement : return 0;
	- Control statements : if, then. Basically control flow statements.
	- Looping statements or Iteration statements : while(..), do (...) while, for(..)
	- Expression statements or Evaluation statements : ==, +=
- Block statements : begins with '{' and finishes with '}' with any type of valid statement
	- Named
	- Unamed
- Complex statements : Structured with a function, like int main() and a block statement afterward
	- Function statement : int main() {...}
- Compound statements : like a chemical compound, it is made by 2 or more simple or complex statements within a block statement.

# Functions :rocket:
They are the basis of any program, they perform one or mulptiple statements to answer to a major or a minor problem in our program. Each function solves a particular problem in our program, and the more yyou adress every chunk of your problem by using function, you are making it more consistent.

## Function Key features :gear:

- Every function is callable, meaning you can invoke it in other functions.
- A program can be summarized in small chunks of problems, resolved by functions.

## Function Key parts  :eyes:
- Function signature
	- Function identifier : The name of the function : e.g : int **main**() {}
	- Function Block : the statement block associated with the function, e.g : int main() **{}** 
	- Function Parameter list : Values passed into the function, e.g : int main**()** {}
- Function return value type : The data type we want, e.g : **int** main(){}
- Function return statement : The data type we want in return, e.g return **int**;

### Function identifiers 

There are plenty ways to name your function but for good practices you shoud follow those rules

- Be descriptive : Don't name it, describe it. e.g : logarithmCalculator 
- Write it in camelcase, snakecase, or lowercase (No uppercase).
	- camel-case : calculateIncomeTax
	- snake-case : calculate-income-tax
	- lowercase : calculateincometax

We think that snake-case is better for longer function identifiers, and camel-case better for the shorter ones.

N.B : Preprocessor directives should always be written in uppercase separated by underscores : FOLLOW_INT_GEO

### Function block 

Function blocks should always have the right amount of lines for good programming practices reasons. Between **25 to 50** lines is good in your terminal.

Remember, it's about adressing subproblems to resolve the bigger ones

### Function return values 

They are specified at the beginning of the functions, and if there is no return value we use "void".
e.g : void main(){}

Return statements can be really different : 
	- return 0; (means there is no problem) 
	- return 1;

### Function parameters

A parameter contains : 
- A data type 
- An identifier

In order to declare a string data type, you have to use *'char*'*

‘‘‘
void printWord(char* word){
	printf(%s, word);

}
‘‘‘
 

