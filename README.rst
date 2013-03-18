pyfmt
=====

Formats Python programs based on PEP8 guidelines, reading input files over
`stdin` and producing a reformatted result on `stdout`.

This tool is inspired by the simplicity of other Unix formatters, specifically
the `BSD fmt` tool.

In its simplest case, (given some python file) this is how its usage would
look::

    $ cat file.py | pyfmt

    # some python's file contents
    from foo import bar

    def main():
        print 'Hello World!'
