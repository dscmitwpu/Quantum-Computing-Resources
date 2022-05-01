# <a href="https://dscmitwpu.github.io/Quantum-Computing-Resources/">Resources For Quantum Computing</a> 


## Physics

First, no knowledge of physics is required. In fact, mostly as a personal challenge, I will teach this subject without any physics. Of course, you’ll end up learning a lot of the mechanical aspects and abstractions of physical models, but we won’t mention things like atoms and energy.

Quantum Computing, like all things you’d like to be good at, requires mathematics. You might have to be acquainted with some pretty complex mathematics, depending on how deep you want to go. But this is not research or a graduate level subject. We only have time to scratch the surface of the topic. But you will still need to learn some new mathematics, and I’m going to require that you already know some before we even get started.

## Complex numbers

Obviously you know about real numbers and functions of them, like polynomials, exponentials, and logarithms. But how about complex numbers? If not, the [Wikipedia article](https://en.wikipedia.org/wiki/Complex_number) doubles as a very good tutorial. Quickly being able to do complex arithmetic will be essential! If I say, “using Euler’s identity we can show...” then I expect that you have at least heard about this! 

## Linear algebra

Quantum mechanics is just applied linear algebra. By the end of the subject, you’ll be an expert on such. But you should come in familiar with some basic concepts. Review what you need to about linear algebra using, for example, [this MIT Open Ware course](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/index.htm). Things that will come up again and again are concepts such as: basis, dimension, norm, inner product, orthogonality, matrices, adjoint, and eigenvalues. These should all be familiar to you before we start.

## Probability

Quantum physics is well-known for its random nature. “God does not play dice!” Einstein protested as he tried to come up with a successor theory with perfect predictive power. Sometimes a quantum computation will produce an exact and deterministic outcome. But this is also a probabilistic statement — the outcome happens with probability 1. The percentage of quantum protocols that produce a random outcome is 75%, and this is true within plus or minus 5 percent points, 19 times out of 20. If you didn’t understand that, you need to review your basic discrete probability theory! Read these notes ([pdf](http://theory.stanford.edu/~trevisan/notes/notesprob.pdf)).

## O-notation

Quantum computing is about “speed-ups”. What is speed? The way computer scientists talk about speed is the language of complexity (not the same as complex numbers!). It is essential that you understand statements that use the “oh” notation. Start with [this article](https://en.wikipedia.org/wiki/Big_O_notation). If you like videos, try [this one](https://www.youtube.com/watch?v=Z0sovxyD7-Q). 

## Programming

We will be doing programming in this subject. It will all be done in Python. However, you won’t need to install anything because we will use IDEs and [Google Colab](https://colab.research.google.com/). I’m not going to link to any resources because it would probably be overkill and there’s nothing like learning some things on the job and how to be resourceful. Basically, you should be able to fire up a Colab instance, import numpy, create a few matrices and vectors, and multiply them together. If you don’t yet know how to do that, take 30 minutes to figure it out.

## Additional Resources

*Textbooks*

Quantum Computation and Quantum Information: 10th Anniversary Edition, by Michael Nielsen and Isaac Chuang.

Quantum Computing: An Applied Approach, by Jack Hidary.

Programming Quantum Computers, by Eric Johnston, Nic Harriagn, and Mercedes Gimeno-Segovia.

*Quantum Programming environments with great documentation*

Q#: https://docs.microsoft.com/en-us/quantum/language/?view=qsharp-preview

Qiskit: https://qiskit.org/

Cirq: https://github.com/quantumlib/Cirq

*Selected lecture notes*

An Introduction to Quantum Computing, by Scott Aaronson: https://www.scottaaronson.com/qclec.pdf.

Quantum Computer Programming, by Will Zeng *et al*: https://cs269q.stanford.edu/syllabus.html.

*Experimental*

Quantum computing for the very curious, by Andy Matuschak and Michael Nielsen: https://quantum.country/qcvc.

Quirk, by Craig Gidney, https://algassert.com/quirk.
