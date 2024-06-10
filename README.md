## Theano

Theano is a Python library that allows us to evaluate mathematical operations including multi-dimensional arrays efficiently. It is mostly used in building Deep Learning Projects. Theano works way faster on the Graphics Processing Unit (GPU) rather than on the CPU. Theano attains high speeds that give tough competition to C implementations for problems involving large amounts of data. It can take advantage of GPUs, making it perform better than C on a CPU by considerable orders of magnitude under certain circumstances. 
Theano also knows how to take structures and convert them into very efficient code that uses Numpy and some native libraries. It is mainly designed to handle the types of computation required for large neural network algorithms used in Deep Learning. That is why, Theanos is a trendy library in the field of Deep Learning.

### Why Theano?

By looking at the complexity of the computational graphs, you will now be able to understand the purpose behind developing Theano. A typical compiler would provide local optimizations in the program as it never looks at the entire computation as a single unit.
Theano implements very advanced optimization techniques to optimize the full computational graph. It combines the aspects of Algebra with aspects of an optimizing compiler. A part of the graph may be compiled into C-language code. The evaluation speed is critical for repeated calculations, and Theano meets this purpose by generating a very efficient code.

## What makes it special?

From a functional and performance perspective, this library:

1. Creates an expression that is evaluated by a Theano function.
2. Allows for differentiation of multiple variables, matrix computations, and gradient calculations with ease.
3. Automatically generates symbolic graphs that can be visualized using a library and the pydotprint function.

These graphs can be highly complex, and Theano applies many advanced optimization techniques (algebra and compilation) to them.

These techniques consider the overall graph to generate highly efficient code, especially in the context of repetitive calculations.

It doesn’t rely solely on local optimization techniques but can also reorganize calculations (order, repetitions) to make them faster, similar to different algorithms for searching a word in a text that can vary in speed (O(n), O(n²)).

The Theano function acts as a bridge to inject compiled C code into the runtime (the software responsible for program execution).
