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

