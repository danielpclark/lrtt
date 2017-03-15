# Learn Ruby Through Testing

**TEST DRIVEN DOCUMENTATION**

There are many "documented" things in Ruby which assume a certain level of understanding.
Even with a vast understanding of Ruby itself these foreign concepts aren't understood by
the very basic description given in the documentation.  Without prior knowledge from another
system or language it's difficult to derive what things are for and how they're supposed to
be used.  **The purpose of this project is to learn the difficult/foreign parts of ruby through
testing (TDD) and then write how-to READMEs on each subject.**  Any README or test is open
to be improved upon and contribution to this project is encouraged.

The structure for this will be straight forward: Every subject will get its own folder in the
`doc` directory by its name in which a README.md will be put explaining a few core things (1)
what (2) how it may be used with code block examples.  Directory structure in doc and test will
be reflected exactly as you would require it eg: in `doc` 'io/console/' would be two directories
each with a README.md and in `test` io will be a test `test/io_test.rb` and console will be a test
in a directory `test/io/console_test.rb`.

For now there is a lot of liberty in how this will be done.  When a test is being written in the
red-green-refactor phase I'd like a comment to be written above the test about what is expected
(as in 'I guess this works this way').  If there is no guess then you should have written in the
README for library the (I know) 'this works this way'.  As a solid understanding of how it works
is attained you may then remove the comment above the test providing that you've written
documentation with examples.

It would be nice if conclusions in the READMEs have some description as to how you came about
that conclusion.

# Areas of Interest

_You may add to this list._

* [ ] Process
* [ ] Signal
* [ ] DRb
* [ ] Mutex_m
* [ ] PTY
* [ ] Fiber
* [ ] Thread
* [ ] WeakRef
* [ ] Shell
* [ ] Rinda


These can be marked as completed if documentation examples have been provided for all methods
within them.  They're still open for updates afterwards.

# Issues

Open as many issues as you'd like on Ruby's core or stdlib that you believe needs more explanation.

# LICENSE

The MIT License (MIT)

Copyright (C) 2017 by Daniel P. Clark & the Learn Ruby Through Testing Team

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
