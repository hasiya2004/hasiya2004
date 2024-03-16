```python

#[derive(Debug, PartialEq)]
struct Bio {
    name: String,
    designation: String,
    company: String,
    base: String,
    blog: String,
}

impl Bio {
    fn new() -> Self {
        Bio {
            name: String::from("Hasindu Senarathna"),
            designation: String::from("Data Scientist n Developer"),
            company: String::from("Lazuno"),
            base: String::from("Warakapola , Sri Lanka "),
            blog: String::from("----------------------"),
        }
    }
}

#[derive(Debug, PartialEq)]
struct Stack {
    languages: Vec<String>,
    databases: Vec<String>,
    misc: Vec<String>,
    ongoing: Vec<String>,
}

impl Stack {
    fn new() -> Self {
        Stack {
            languages: vec![
                String::from("Python"),
                String::from("Go"),
                String::from("Shell"),
                String::from("rust"),
                String::from("java"),
                String::from("php"),
                String::from("html"),
                String::from("css"),
                String::from("js"),
            ],
            databases: vec![
                String::from("MySQL"),
                String::from("PostgreSQL"),
                String::from("Mongo"),
                String::from("Redis"),
            ],
            misc: vec![
                String::from("Docker"),
                String::from("Celery"),
            ],
            ongoing: vec![
                String::from("Django"),
                String::from("GraphQL"),
            ],
        }
    }
}

#[derive(Debug, PartialEq)]
struct Social {
    twitter: String,
    linkedin: String,
}

impl Social {
    fn new() -> Self {
        Social {
            twitter: String::from("Hasinduse"),
            linkedin: String::from("Hasindu Senarathne"),
        }
    }
}

fn main() {
    let bio = Bio::new();
    let stack = Stack::new();
    let social = Social::new();

    println!("Bio: {:?}", bio);
    println!("Stack: {:?}", stack);
    println!("Social: {:?}", social);
}


⭐️ From [Hasindu](https://github.com/hasiya2004)
