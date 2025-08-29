fn main() {
    let mut s = String::from("Hello");
    s.push('!');
    s.push_str(" Welcome");
    println!("{}", s); // Output: "Hello! Welcome"

    for c in s.chars() {
        println!("{}", c);
    }

    for b in s.bytes() {
        println!("{}", b);
    }

    for (i, c) in s.char_indices() {
        println!("Index: {}, Char: {}", i, c);
    }
}


