  
  <h1 align='center'> LINVAST - Language-INVariant AST library <br>
  Extending LINVAST with new programming language - Java </h1>
  
  <p>
    Student project on course Software verification, Master Degree Studies, University of Belgrade, Faculty of Mathematics
    <br>
       
 <!-- ABOUT THE PROJECT -->
## About LINVAST

_LINVAST is a set of libraries which provide common AST API for many programming languages by abstracting [ANTLR](https://www.antlr.org/) parse trees. Currently, the main focus of the project is the imperative programming paradigm, with supported languages: `C`, `Lua`._

### _Motivation and project description_
> _There are many programming languages out there and, even though their syntax might be different, they often derive from or use certain universal programming concepts. We also call that a  _way of writing code_  or, more commonly, a programming paradigm. The motivation for LINVAST came from the inability to find a shared API for every programming language that is a part of a procedural paradigm. LINVAST aims to create a common abstraction for imperative (but also procedural, OO, script and, through a few concepts, functional) programming paradigm so that it is possible to view many different programming languages on the same level of abstraction._
> 
> _LINVAST can theoretically work with any programming language as long as the adapter for that language is written (hence,  _Language Invariant_). Adapters (or, in further text,  _Builders_) serve as an intermediary between ANTLR parse trees and language-invariant ASTs. Builders are used to generate AST from a parse tree and they are implemented differently for every programming language due to native differences in parse trees. LINVAST provides intuitive API for generating and traversing generated ASTs and also provides already implemented visitors for common AST operations such as expression evaluation._
> 
> _LINVAST was made as a proof of concept for my MSc thesis (_Semantic comparison of structurally similar imperative code segments_) but has grown with aim to become fully operational and manageable long-term. LINVAST can be used as a tool to generate serialized AST in JSON, and provides intuitive API which is used in many standalone programs which use LINVAST API to visualize or compare generated ASTs._

## About the project
The purpose of this project was to expand original LINVAST project with Builders and to generate AST for language `Java`.
In order to extend LINVAST with new language, you should create (or use already made) ANTLR4 grammar files, create lexer and parser for your grammar, and implement the _Builder_ for your language. The main students' task in the project was designing, implementing and testing  the _Builder_ for `Java`. The task was divided in 4 parts, each covering some consistent part of the grammar: _Types_, _Declarations_, _Functions_ and _Expressions_.

`Java` is the first Object-oriented programming language supported by LINVAST.

<!-- LANGUAGES AND TECHNOLOGIES USED -->
## Languages and technologies used

* Code was written using [Visual Studio 2019]()
* C# Language


<!-- CONTACT -->
## Contact

* Marija Katić | katic.marija.97@gmail.com, mr16032@alas.matf.bg.ac.rs | https://github.com/marijakatic
* Dara Milojković | milojkovic.dara@gmail.com, mi16100@alas.matf.bg.ac.rs | https://github.com/Dara123M
