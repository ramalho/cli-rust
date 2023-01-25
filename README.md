# cli-rust
Examples from (or inspired by) the book
[_Command-line Rust_](https://www.oreilly.com/library/view/command-line-rust/9781098109424/),
by Ken Youens-Clark.

## Notes

### First session (2.5h)

I read chapters 1 and 2, building the examples (except the `true` and `false` programs).

Before today, I had only written a "Hello World" program in Rust.
I also tried to make ChatGPT write my favorite Unicode finder
example for me,
but it repeatedly suggested using crates providing the Unicode data which were not available.

For a systems language, I am amazed at Rust's usability.
The compiler error messages are fantastic.

I did not like the subtle Rust shortcut of ommiting the semicolon
after the last line of a function to make that line the return value.

I liked the project-based approach chosen by the author.

On the other hand, the book skips a lot of details or 
gives only superficial explanations
about some of the Rust concepts required by the examples,
such as the use of `&` prefix in function arguments.

Reading [_The Book_](https://doc.rust-lang.org/book/) alongside will be good.

Youens-Clark actually recommends this in the preface:

> This book will focus on the practical side of things, showing you what you need to know to get things done. I’ll leave the nitty-gritty to more comprehensive books such as Programming Rust, 2nd ed., by Jim Blandy, Jason Orendorff, and Leonora F. S. Tindall (O’Reilly) and The Rust Programming Language by Steve Klabnik and Carol Nichols (No Starch Press). I highly recommend that you read one or both of those along with this book to dig deeper into the language itself.
