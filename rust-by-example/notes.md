Compiling -> ´rustc <file>´
Example with running the compiled program if successful:
´rustc hello-world/formatted-print.rs && ./formatted-print´

Nope, we have to compile to a /target/ folder, or else we can't see that the files should be ignored.

Hmm, lets see if there is a flag for target with rustc...
Yup, -o sets target file.


´rustc -o target/compiledrust hello-world/formatted-print.rs && ./target/compiledrust´

Remember to create target folder
Current progress:
[Debug](https://doc.rust-lang.org/stable/rust-by-example/hello/print/print_debug.html)
