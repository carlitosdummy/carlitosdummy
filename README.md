```rust
impl Developer for AboutMe {
    fn about_me(&self) -> AboutMe {
        AboutMe {
            name: "dummy",
            area: "cs",
            age: 20,
        }
    }

    fn skills(&self) -> Skills {
        Skills {
            languages: vec!["python", "rust", "java", "html", "css"],
        }
    }
}
```
