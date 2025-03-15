+++
date = '2025-03-14T19:41:42+01:00'
title = 'Abstract Syntax Tree'
+++

# What is Abstract Syntax Tree ?

Here I will present to you the results of my research on AST, which helped me to solve the [AST Deobfuscation](https://www.root-me.org/fr/Challenges/Web-Client/AST-Deobfuscation) challenge on RootMe. 

Abstract Syntax Tree is a data structure to represent the structure of a program. It is a tree representation of the abstract syntax structure of text written in a formal language. 

![alt text](AST1.png)

We call this structure "Abstract" because it does not show every details appearing in the original syntax. 

![alt text](AST2.png)

Converting a program in AST is very useful for many reasons: 
-   Compiling to Machine Code
-   Code Optimization
-   Bug Detection 
-   Advanced Deobfuscation
-   etc..

The RootMe challenge wasn't a deobfuscation using AST or a deobfuscation of the AST itself, but simply a translation of the AST into executable code.

After the translation, we obtain a cryptographic function that, upon execution, returns the flag.


