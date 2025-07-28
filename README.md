
# push_swap

Project developed as part of the 42 Lisboa curriculum.

## 🧠 Objective

Sort a stack of integers using a limited set of operations and the smallest number of moves possible.

This project is divided into two programs:

1. `push_swap`: Generates the list of operations to sort the stack.
2. `checker`: Verifies if a given sequence of operations sorts the stack correctly.

## 📦 Allowed Operations

- `sa`, `sb`, `ss`: Swap the first two elements of stack A, B, or both.
- `pa`, `pb`: Push the top element from one stack to another.
- `ra`, `rb`, `rr`: Rotate stack A, B, or both (first element becomes last).
- `rra`, `rrb`, `rrr`: Reverse rotate A, B, or both (last element becomes first).

## 🔧 Features

- Input validation (only integers, no duplicates)
- Custom sorting logic depending on input size:
  - Hardcoded logic for 2–5 elements
  - Optimized radix sort for larger datasets
- Efficient use of operations to minimize total moves
- Bonus: `checker` program to validate move sequences

## 🛠️ How to Compile

```bash
make
```

## ▶️ How to Use

```bash
./push_swap 3 2 1
```

This will output the list of operations to sort the stack.

To validate using `checker`:

```bash
./push_swap 3 2 1 | ./checker 3 2 1
```

## 📚 What I Learned

- Stack manipulation and algorithmic thinking
- Input parsing and validation
- Sorting algorithm optimization (radix, insertion logic)
- Creating reusable data structures in C (linked lists)
- Handling edge cases and minimizing instruction count

## 🧑‍💻 Author

[Kayki Rocha](https://github.com/UnderOfAll) – 42 Lisboa Student
