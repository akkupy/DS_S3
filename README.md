# DS_S3
Semester 3 Data Structure Works..



### Experiment 6.

[stack_array.c](https://github.com/akkupy/DS_S3/blob/main/Exp_6/stack_array.c) - Implementation of stack and multiple stack using 1D array.
```

1.Push
2.Pop
3.Peek
4.Display
5.Exit
Enter your choice:1
Enter the item to be pushed:50

1.Push
2.Pop
3.Peek
4.Display
5.Exit
Enter your choice:1
Enter the item to be pushed:51

1.Push
2.Pop
3.Peek
4.Display
5.Exit
Enter your choice:3
The top item is:51
1.Push
2.Pop
3.Peek
4.Display
5.Exit
Enter your choice:4
Stack contents are:51 50 
1.Push
2.Pop
3.Peek
4.Display
5.Exit
Enter your choice:2
The popped value is:51
1.Push
2.Pop
3.Peek
4.Display
5.Exit
Enter your choice:4
Stack contents are:50 
1.Push
2.Pop
3.Peek
4.Display
5.Exit
Enter your choice:5

```  


### Experiment 7.

[stack_linkedlist.c](https://github.com/akkupy/DS_S3/blob/main/Exp_7/stack_linkedlist.c) - Implementation of stack using linked list
```

1. Insert 
2. Delete
3. Display
4. Quit
Enter your Choice : 1

value to be inserted:50

1. Insert 
2. Delete
3. Display
4. Quit
Enter your Choice : 1

value to be inserted:51

1. Insert
2. Delete
3. Display
4. Quit
Enter your Choice : 1

value to be inserted:52

1. Insert
2. Delete
3. Display
4. Quit
Enter your Choice : 3
52 --> 51 --> 50
1. Insert
2. Delete
3. Display
4. Quit
Enter your Choice : 2

1. Insert
2. Delete
3. Display
4. Quit
Enter your Choice : 3
51 --> 50
1. Insert
2. Delete
3. Display
4. Quit
Enter your Choice : 4

```  
### Experiment 8.

[infix_postfix.c](https://github.com/akkupy/DS_S3/blob/main/Exp_8/infix_postfix.c) - Infix to Postfix Conversion Using Stack
```
Enter the Expression : A*B+C/D^2

 Token: A        stack :         postfix : A
 Token: *        stack : *       postfix : A
 Token: B        stack : *       postfix : A B
 Token: +        stack : +       postfix : A B *
 Token: C        stack : +       postfix : A B * C
 Token: /        stack : + /     postfix : A B * C
 Token: D        stack : + /     postfix : A B * C D
 Token: ^        stack : + / ^   postfix : A B * C D
 Token: 2        stack : + / ^   postfix : A B * C D 2 
 Postfix: AB*CD2^/+
```  

### Experiment 9.

[postfix_eval.c](https://github.com/akkupy/DS_S3/blob/main/Exp_9/postfix_eval.c) - Evaluation of postfix expression using stack.
```
Enter the postfix expression:
56*73*/

The result is : 1.428571
```  