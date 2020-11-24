# BinaryTree
Lab that deals with binary trees, interested in the structural contruction of the tree. 
Assuming each node has three pointers Left(l), Right(r), and Parent(p) with using standard 
pointer based representation. 
To compile: $gcc lab4.c -o lab4
To run: $./lab4 8     
*(instead of 8 could be any number wanted to input for n)
output should look something like this:
n = 8

********** ENCODING 1 **********

+++ The binary tree:
    X
    +---X
        +---|
        +---|
    +---X
        +---X
            +---|
            +---|
        +---X
            +---|
            +---X
                +---X
                    +---|
                    +---|
                +---X
                    +---|
                    +---|

+++ The binary tree:
    NULL

+++ Encoding 1 of tree: 02102110212222

+++ The binary tree:
    X
    +---X
        +---|
        +---|
    +---X
        +---X
            +---|
            +---|
        +---X
            +---|
            +---X
                +---X
                    +---|
                    +---|
                +---X
                    +---|
                    +---|

+++ Original encoding : 02102110212222
+++ Final encoding    : 02102110212222

********** ENCODING 2 **********

+++ The binary tree:
    X
    +---|
    +---X
        +---X
            +---X
                +---|
                +---X
                    +---X
                        +---|
                        +---|
                    +---|
            +---|
        +---X
            +---|
            +---X
                +---|
                +---|

+++ Encoding 2 of tree: 10010010011111
*** Tree is not unique!!! V(1,10) = 2, 8
*** Tree is not unique!!! V(1,12) = 2, 8

+++ The binary tree:
    X
    +---|
    +---X
        +---X
            +---|
            +---|
        +---X
            +---X
                +---|
                +---|
            +---X
                +---X
                    +---|
                    +---|
                +---X
                    +---|
                    +---|

+++ Original encoding : 10010010011111
+++ Final encoding    : 10010010011111
