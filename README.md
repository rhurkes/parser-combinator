# parser-combinator
Rust parser combinator example. Based off of https://bodil.lol/parser-combinators/.

```
There comes a point in the life of every programmer when they find themselves in need of a parser.

The novice programmer will ask, "what is a parser?"

The intermediate programmer will say, "that's easy, I'll write a regular expression."

The master programmer will say, "stand back, I know lex and yacc."

The novice has the right idea.
```

```
In the beginner's mind, as the man said, there are many possibilities. In the expert's mind, there's only the one the expert got used to.
```
- https://en.wikipedia.org/wiki/Shunry%C5%AB_Suzuki#Quotations

- `Parsing` is a process of deriving structure from a stream of data
- A `parser` is something which teases out that structure, in its simplest form, is a function which takes some input and returns either the parsed output along with the remainder of the input, or an error saying "I couldn't parse this."
- `higher order function` is a function that returns a function
- `parser combinator` combines two parsers into a new one
- `functor`
- `predicate` is a function that tests for some condition involving its arguments and returns nil if the condition is false, or some non-nil value if the condition is true. One may think of a predicate as producing a Boolean value, where nil stands for false and anything else stands for true.

- https://stackoverflow.com/questions/7533837/explanation-of-combinators-for-the-working-man/7534575#7534575
- https://stackoverflow.com/questions/97637/good-explanation-of-combinators-for-non-mathematicians
- https://stackoverflow.com/questions/2030863/in-functional-programming-what-is-a-functor/23236777


1. What does `impl` keyword do?
2. How do traits work?
3. How does `Box<>` work?
4. What does `dyn` keyword do?
5. What the hell is `An Opportunity Presents Itself` about?