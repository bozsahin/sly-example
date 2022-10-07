To use this code, do <code>python g2lisp.py</code>

And follow the instructions there.

You need to pip install sly.py first. And you need python3.8 or newer.

In the folder there are source files (.src) for a natural language grammar.

These source files are parsed into IC code (.ic) in the form of a python dict for source's AST.

Once parsed, the current IC code can generate target code (.tc) in the form of Common Lisp expressions.

In g2lisp.py code you can see a fairly involved sly lexer and parser specification, and code generation (ir_.. functions).

enjoy.
-cemB

