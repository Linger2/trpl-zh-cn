# A - 关键字
下面的关键字是Rust程序设计语言的保留字，不能用作标识符，如：函数，变量，参数，结构中的字段，模块，crates，常量，宏，静态值，特性，类型，traits或生命周期的标识符。

### 目前正在使用的关键字

* `as` - 内部转换, disambiguating the specific trait containing an
  item, 或者重命名 `use` 和 `extern crate` 的声明
* `break` - 立即退出一个循环
* `const` - 常量 items 和 常量裸指针
* `continue` - 继续循环下一次迭代
* `crate` - external crate linkage or a macro variable representing the crate
  in which the macro is defined
* `else` - fallback for `if` and `if let` control flow constructs
* `enum` - defining an enumeration
* `extern` - external crate, function, and variable linkage
* `false` - boolean false literal
* `fn` - function definition and function pointer type
* `for` - iterator loop, part of trait impl syntax, and higher-ranked lifetime
  syntax
* `if` - conditional branching
* `impl` - inherent and trait implementation block
* `in` - part of `for` loop syntax
* `let` - variable binding
* `loop` - unconditional, infinite loop
* `match` - pattern matching
* `mod` - module declaration
* `move` - makes a closure take ownership of all its captures
* `mut` - denotes mutability in references, raw pointers, and pattern bindings
* `pub` - denotes public visibility in struct fields, `impl` blocks, and modules
* `ref` - by-reference binding
* `return` - return from function
* `Self` - type alias for the type implementing a trait
* `self` - method subject or current module
* `static` - global variable or lifetime lasting the entire program execution
* `struct` - structure definition
* `super` - parent module of the current module
* `trait` - trait definition
* `true` - boolean true literal
* `type` - type alias and associated type definition
* `unsafe` - denotes unsafe code, functions, traits, and implementations
* `use` - import symbols into scope
* `where` - type constraint clauses
* `while` - conditional loop

### 预留将来使用的关键字

这些关键字没有任何功能，但在Rust中被保留用于未来潜在用途。 

* `abstract`
* `alignof`
* `become`
* `box`
* `do`
* `final`
* `macro`
* `offsetof`
* `override`
* `priv`
* `proc`
* `pure`
* `sizeof`
* `typeof`
* `unsized`
* `virtual`
* `yield`
