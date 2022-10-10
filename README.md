# Python

Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together. Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance. Python supports modules and packages, which encourages program modularity and code reuse. The Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms, and can be freely distributed.

Often, programmers fall in love with Python because of the increased productivity it provides. Since there is no compilation step, the edit-test-debug cycle is incredibly fast. Debugging Python programs is easy: a bug or bad input will never cause a segmentation fault. Instead, when the interpreter discovers an error, it raises an exception. When the program doesn't catch the exception, the interpreter prints a stack trace. A source level debugger allows inspection of local and global variables, evaluation of arbitrary expressions, setting breakpoints, stepping through the code a line at a time, and so on. The debugger is written in Python itself, testifying to Python's introspective power. On the other hand, often the quickest way to debug a program is to add a few print statements to the source: the fast edit-test-debug cycle makes this simple approach very effective.

## Best Practices

1. Create a Code Repository and Implement Version Control
2. Create Readable Documentation
3. Follow Style Guidelines ([PEP 8](https://peps.python.org/pep-0008/), name classes with the CapWords convention)
  - Use proper naming conventions for variables, functions, methods, and more.
  - Variables, functions, methods, packages, modules: this_is_a_variable
  - Classes and exceptions: CapWords
  - Protected methods and internal functions: _single_leading_underscore
  - Private methods: __double_leading_underscore
  - Constants: CAPS_WITH_UNDERSCORES
  - Use 4 spaces for indentation. For more conventions, refer to PEP8. 
4. Correct Broken Code Immediately
5. Use the PyPI Instead of Doing it Yourself
6. The Zen of Python

***
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren’t special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one– and preferably only one –obvious way to do it.
Although that way may not be obvious at first unless you’re Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it’s a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea — let’s do more of those!
***


### Coding

## References

- https://data-flair.training/blogs/python-best-practices/
