## Compilation vs Interpreation
C++ is mostly compiled - note that a language is neither compiled nor interpreted, it's just that
a language is more easily compiled/interpreted than others 

Compilation generates optimzied code and creates an executable that can be run multiple times. However,
interpretation is run every time when the program is run. 

The advantage of compilation is that it can generate fast code by having a holistic overview of the code in comparison to
intepreters that can only see line by line. The disadvantages of compilation include the start up time needed and the
constraints of optimizing dynamic typing which can't be done since it won't know what's going to happen unless the program
is run.

The advantage of interpretation is that it can handle dynamic typing since the interpretation is done while the program
is being run. It also has a low start up time since it goes line by line rather than optimizing the entire code. The
disadvatnages of intepretation is that it uses more memory and takes CPU time.

## Resources

([Stack Overflow Comparison ](https://stackoverflow.com/questions/38491212/difference-between-compiled-and-interpreted-languages/38491646#38491646))
