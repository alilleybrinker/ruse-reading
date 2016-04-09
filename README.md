# Reading on Implementing Scheme

This is a collection of links to materials relevant to the creation of [Ruse][ruse]. These are offered in no particular order, and have varying degrees of relevance to the project.

## Links

[Seven lines of code, three minutes, implement a programming language from scratch](http://matt.might.net/articles/implementing-a-programming-language/): This essay by Matthew Might of the University of Utah discusses the simplicity of implementing the most basic of programming languages: the untyped lambda calculus.

[History of T](http://www.paulgraham.com/thist.html): This essay by Olin Shivers describes the creation of T, billed as "one of the best Lisp implementations". It is a fascinating historical document that provides a lot of color to the history of Lisp in all its forms.

[A lambda is not (necessarily) a closure](https://wingolog.org/archives/2016/02/08/a-lambda-is-not-necessarily-a-closure): This essay by Andy Wingo (of Guile fame), gets into the different ways Guile closures may be implemented at runtime. It's a really interesting discussion of some nitty-gritty details of Guile's implementation.

[Loop optimizations in Guile](http://wingolog.org/archives/2015/07/28/loop-optimizations-in-guile): This essay is also by Andy Wingo, and describes the ways in which loops in Guile are optimized.

[Revisiting common subexpression elimination in Guile](http://wingolog.org/archives/2014/08/25/revisiting-common-subexpression-elimination-in-guile): Sensing a theme? This is another essay by Andy Wingo, this time addressing the ways in which subexpressions may be eliminated to improve performance of Guile programs.

[Flow analysis in Guile](http://wingolog.org/archives/2014/07/01/flow-analysis-in-guile): In the fourth essay of Andy Wingo's, he addresses how program flow analysis is used to improve the performance of Guile programs.

[ruse]: https://github.com/ruse-lang/ruse

