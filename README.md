# bitnine-Apache-AGE-coding-test
 
This repo contains the solution to question 1 and question 2


# [ Question No. 1 ]

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
