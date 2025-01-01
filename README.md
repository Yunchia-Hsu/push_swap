# push_swap
It is a sorting algorithm practice in C. We created a program attempting to use the minimum number of moves to sort a set of integers with 2 stacks. 
The program output the shortest list of moves that found.

### Running 

The first number indicates the number at the top of the stack. 

`./push_swap 5 3 1 2 4`

or 

`./push_swap "5 3 1 2 4"`

### Moves to sort numbers

- pa - pushed from stack b to stack a
- pb - pushed from stack a to stack b
- sa - swaps the top two elements of stack a
- sb - swaps the top two elements of stack b
- ss - performs sa and sb simultaneously
- ra - shifts all elements of stack a up one (first becomes last)
- rb - shifts all elements of stack b up one (first becomes last)
- rr - performs ra and rb simultaneously
- rra - shifts all elements of stack a down one (last becomes first)
- rrb - shifts all elements of stack a down one (last becomes first)
- rrr - performs rra and rrb simultaneously
