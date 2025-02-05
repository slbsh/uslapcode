# Woof Woof.. oh wait wrong one
Write a program to print all files given in the cmdline args.  
`cat README.md` should print this file.  

music: **Thou - Blessings of the Highest Order**

# Rules
- multiple files can be given, and should be printed on a newline
- no gippidy!

# Tips
This is the first one so we got tips :)
- `dbg!(&val)` or `println!("{:?}", val)` to debug stuff
- `cargo run -- README.md` to run the program with README.md as argument
- `cargo clippy` for clipperino :L

# Resources
- `std::env::args`
- `std::fs::read_to_string`
- `println!` macro
