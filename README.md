// ===============================================
//  Hasindu Senarathna | Data Science & AI 🇱🇰
// ===============================================

struct Developer {
    name: &'static str,
    uni:  &'static str,
    tech: Vec<&'static str>,
    focus: Vec<&'static str>,
}

fn main() {
    let hasindu = Developer {
        name:  "Hasindu Senarathna",
        uni:   "SLTC Research University",
        tech:  vec!["Python", "Rust", "SQL", "Kotlin", "Git", "Machine Learning"],
        focus: vec!["AI/ML Models", "Data Analytics", "Android Dev", "Open Source"],
    };

    println!("👋 Hi, I'm {} at {}", hasindu.name, hasindu.uni);
    println!("🛠  Tech Stack: {:?}", hasindu.tech);
    println!("🚀 Current Focus: {:?}", hasindu.focus);
    println!("📫 Connect: github.com/hasiya2004");
}
