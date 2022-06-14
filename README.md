# Monty
monty is an interpreter of Monty ByteCodes files, which is a scripting language just like Python.

# More Info

# Data structures
 
 Please use the following data structures for this project. Don’t forget to include them in your header file.
 
```/**
 * struct stack_s - doubly linked list representation of a stack (or queue)
 * @n: integer
 * @prev: points to the previous element of the stack (or queue)
 * @next: points to the next element of the stack (or queue)
 *
 * Description: doubly linked list node structure
 * for stack, queues, LIFO, FIFO
 */
typedef struct stack_s
{
        int n;
        struct stack_s *prev;
        struct stack_s *next;
} stack_t;```
