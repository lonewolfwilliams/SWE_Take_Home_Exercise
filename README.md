# Prefix Calculator

You are to write a program that accepts numerical calculations in prefix notation, such as + 5 7 or - 12 * 2 6.

You can make the following assumptions:

* The system should support the operators {+, -, *, /} which all take exactly two args.
* The input literals are positive integers
* Calculations can be done in the floating-point or integer domain
* Handling division by zero is unimportant; program can crash or do anything if that arises.
* You are free to use any programming lanugage of choice.

### Sample input (caret prompt for clarity only):
```
> 3
3
> + 1 2
3
> + 1 * 2 3
7
> + * 1 2 3
5
> - / 10 + 1 1 * 1 2
3
> - 0 3
-3
> / 3 2
1 (or 1.5)
```

## Additional Bonus #1
Implement your calculator in infix notation with support for full-parenthesized operands. It's OK want to assume that all the tokens are space-separated, including the parenethesis tokens

### Sample input (caret prompt for clarity only):
```
> 3
> ( 1 + 2 )
> ( 1 + ( 2 * 3 ) )
> ( ( 1 * 2 ) + 3 )
> ( ( ( 1 + 1 ) / 10 ) - ( 1 * 2 ) )
```

## Additional Bonus #2
Create a web-based version of your calculator, as in a service with a RESTful interface. The goal would be to be able to interact with your calculator over the internet vs a standalone desktop based application.

# Deliverables:
* A GitHub repo with your working code and accompanying test cases

