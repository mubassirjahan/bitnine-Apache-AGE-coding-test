# bitnine-Apache-AGE-coding-test
 
This repo contains the solution to question 1 and question 2


# [Question No. 1]

## Node is defined as follows :
```
typedef struct Node
{
TypeTag type;
} Node;
typedef enum TypeTag {
...
}
Using this structure, please write a function that returns fibonacci sequence based on the following arithmetic operations (+, -, *, /) and conditions.
The fibonacci function should be implemented using Dynamic Programming.
main()
{
Node *add = (*makeFunc(ADD))(10, 6);
Node *mul = (*makeFunc(MUL))(5, 4);
Node *sub = (*makeFunc(SUB))(mul, add);
Node *fibo = (*makeFunc(SUB))(sub, NULL);
calc(add);
calc(mul);
calc(sub);
calc(fibo)
}
Output
add : 16
mul : 20
sub : -4
fibo : 2

``` 
# [Question no. 2]
▪ Implement the following piecewise recurrence relation in the 3 different ways.

▪ Explain the differences (advantages, disadvantages) between the 3.

▪ Must be written in C

#The Problem 
```
F(n) = F(n-3) + F(n -2) where F(0) = 0, F(1) = 1, and F(2) = 2.
Assume that n will be less than or equal to the maximum integer value and non-negative. You only need to
write the function(s).


## Troubleshooting

If you encounter any issues compiling or running the program, please refer to the error messages generated in the IDE terminal for assistance. Make sure that all required dependencies are installed and that the commands are being properly formatted from IDE.     

For further assistance feel free to email : mubassir.jahan@outlook.com

## Contributors

- Mubassir Jahan (https://github.com/mubassirjahan)
- copyright @2023

