# Ex. No: 15C - Expression Tree with Inorder and Postorder Traversal

## AIM:
To write a Python program to build the given expression tree and print the inorder and postorder traversals.

---

## ALGORITHM:

1. **Start the program.**
2. Import the required modules (`build` and `Node` from `binarytree`).
3. Define a list `x` representing the expression tree in pre-order fashion (with `None` for missing nodes).
4. Use the `build()` function to generate the binary tree.
5. Print the **inorder** and **postorder** traversal of the tree.
6. **End the program.**

---

## PROGRAM:

```
Name : Vimaleshwari S
Reg No : 212223060304
from binarytree import Node,build
l=['/','*','+','+',4,'-',2,3,1,None,None,9,5,None,None]
x=build(l)
print(x.inorder)
print(x.postorder)
```

## OUTPUT

<img width="1121" height="193" alt="image" src="https://github.com/user-attachments/assets/9d8765b7-1fbf-4a82-8aff-e9a853892014" />

## RESULT
Thus,a Python program to build the given expression tree and print the inorder and postorder traversals is successfully executed.
