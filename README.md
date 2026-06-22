```rust
// ===============================================
//  Hasindu Senarathna
//  Data Science Student | AI Enthusiast
// ===============================================

struct Developer {
    name: &'static str,
    university: &'static str,
    field: &'static str,
    location: &'static str,
    interests: Vec<&'static str>,
}

fn main() {
    let hasindu = Developer {
        name: "Hasindu Senarathna",
        university: "SLTC Research University",
        field: "Data Science",
        location: "Sri Lanka",
        interests: vec![
            "Artificial Intelligence",
            "Machine Learning",
            "Data Science",
            "Python Development",
            "Kotlin",
            "Android Development",
            "Open Source"
        ],
    };

    println!("👋 Hi, I'm {}", hasindu.name);
    println!("🎓 Studying {}", hasindu.field);
    println!("🏫 {}", hasindu.university);
    println!("🌍 {}", hasindu.location);

    println!("\n🚀 Current Goals");
    println!("├─ Learning AI & Machine Learning");
    println!("├─ Building Real-World Projects");
    println!("├─ Exploring Data Analytics");
    println!("├─ Contributing to Open Source");
    println!("└─ Growing as a Software Engineer");

    println!("\n🛠 Tech Stack");
    println!("├─ Python");
    println!("├─ Rust");
    println!("├─ SQL");
    println!("├─ Kotlin");
    println!("├─ Git & GitHub");
    println!("└─ Machine Learning");

    println!("\n📈 Currently Working On");
    println!("├─ AI Models");
    println!("├─ Data Science Projects");
    println!("├─ Android Applications");
    println!("└─ Personal Portfolio");

    println!("\n📫 Connect With Me");
    println!("GitHub: github.com/hasiya2004");
}

