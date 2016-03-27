# Gradual Typing for Functional Languages

Presented by [Jaseem Abid][presenter]

Static and dynamic type systems have well-known strengths and weaknesses, and
each is better suited for different programming tasks. There have been many
efforts to integrate static and dynamic typing and thereby combine the benefits
of both typing disciplines in the same language. The flexibility of static
typing can be improved by adding a type Dynamic and a typecase form. The safety
and performance of dynamic typing can be improved by adding optional type
annotations or by performing type inference (as in soft typing). However, there
has been little formal work on type systems that allow a programmer-controlled
migration between dynamic and static typing.

In this paper we present a solution based on the intuition that the structure of
a type may be partially known/unknown at compile-time and the job of the type
system is to catch incompatibilities between the known parts of types. We define
the static and dynamic semantics of a λ calculus with optional type annotations
and we prove that its type system is sound with respect to the simply-typed λ
calculus for fully-annotated terms. We prove that this calculus is type safe and
that the cost of dynamism is pay-as-you-go.

We will also look into other candidates in this space and what they do
differently - like flowtype for js, typed racket, mypy etc.

## Links

- [Paper][paper]
- [Slides][slides]
- [Keynote File][keynote]
- [Plaintext Slides][plaintext]
- [Meetup Page][meetup]

## Supplementary reading:

- http://wphomes.soic.indiana.edu/jsiek/what-is-gradual-typing/
- http://siek.blogspot.in/2012/07/crash-course-on-notation-in-programming.html
- http://samth.github.io/gradual-typing-bib/

[presenter]: https://twitter.com/jaseemabid
[paper]: http://ecee.colorado.edu/~siek/pubs/pubs/2006/siek06_gradual.pdf
[slides]: ./gradual_typing.pdf
[keynote]: ./gradual_typing.key
[plaintext]: ./gradual_typing.org
[meetup]: http://www.meetup.com/Papers-we-love-Bangalore/events/229428090/
