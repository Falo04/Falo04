```rust
#[derive(Debug)]
struct AboutMe {
    name: &'static str,
    designation: &'static str,
    base: &'static str,
}

#[derive(Debug)]
struct Stack {
    backend: Vec<&'static str>,
    frontend: Vec<&'static str>,
    misc: Vec<&'static str>,
}

fn main() {
    let me = AboutMe {
        name: "Felix",
        designation: "Cybersecurity",
        base: "Ingolstadt, Germany",
    };

    let stack = Stack {
        backend: vec!["Rust", "Go", "Python", "C", "C++"],
        frontend: vec!["React", "Angular", "Typescript", "Tailwind"],
        misc: vec!["Docker", "Nginx", "PostgreSQL"],
    };

    println!("About Me:\n{:#?}", me);
    println!("\nMy Stack:\n{:#?}", stack);
}
```


###
![](https://raw.githubusercontent.com/Falo04/github-stats/master/generated/overview.svg#gh-dark-mode-only)
![](https://raw.githubusercontent.com/Falo04/github-stats/master/generated/overview.svg#gh-light-mode-only)
![](https://raw.githubusercontent.com/Falo04/github-stats/master/generated/languages.svg#gh-dark-mode-only)
![](https://raw.githubusercontent.com/Falo04/github-stats/master/generated/languages.svg#gh-light-mode-only)
