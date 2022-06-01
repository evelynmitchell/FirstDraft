---
id: er2ygm2brn7dpwlazfb0akp
title: ComputerScience
desc: ''
updated: 1648346950688
created: 1648346950688
---

Type Theory
[Homotopy Type Theory](https://www.cs.cmu.edu/~rwh/courses/hott/)



[[compress]] https://caseymuratori.com/blog_0015
"Rather, it means that the development of the code is optimized  —  that the code is structured in such a way so as to minimize the amount of human effort necessary to type it, get it working, modify it, and debug it enough for it to be shippable. "

"Like a good compressor, I don’t reuse anything until I have at least two instances of it occurring."

“make your code usable before you try to make it reusable”. 

'I always begin by just typing out exactly what I want to happen in each specific case, without any regard to “correctness” or “abstraction” or any other buzzword, and I get that working. Then, when I find myself doing the same thing a second time somewhere else, that is when I pull out the reusable portion and share it, effectively “compressing” the code. I like “compress” better as an analogy, because it means something useful, as opposed to the often-used “abstracting”, which doesn’t really imply anything useful. Who cares if code is abstract? "

"Waiting until there are (at least) two examples of a piece of code means I not only save time thinking about how to reuse it until I know I really need to, but it also means I always have at least two different real examples of what the code has to do before I try to make it reusable. This is crucial for efficiency, because if you only have one example, or worse, no examples (in the case of code written preemptively), then you are very likely to make mistakes in the way you write it and end up with code that isn’t conveniently reusable. This leads to even more wasted time once you go to use it, because either it will be cumbersome, or you will have to redo it to make it work the way you need it to. So I try very hard to never make code “prematurely reusable”, to evoke Knuth. "

"Finally, the underlying assumption in all of this is, if you compress your code to a nice compact form, it is easy to read, because there’s a minimal amount of it, and the semantics tend to mirror the real “language” of the problem, because like a real language, those things that are expressed most often are given their own names and are used consistently. Well-compressed code is also easy to maintain, because all the places in the code that are doing identical things all go through the same paths, but code that is unique is not needlessly complicated or separated from its use. Finally, well-compressed code is easy to extend, because producing more code that does similar operations is simple, as all the necessary code is there in a nicely recomposable way. "