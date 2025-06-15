```python
# 👨‍💻 Hasindu Senarathna | Self-Taught Python AI Developer

class Developer:
    def __init__(self):
        self.name = "Hasindu Senarathna"
        self.location = "🇱🇰 Sri Lanka"
        self.status = "🧠 Self-taught | 💻 Learning Online for Free"
        self.role = "Python AI Developer"
        self.website = "🌐 https://nukebirds.com"
        self.email = "📧 hasindusenaratna@gmail.com"
        self.goal = "🚗 Buy BMW M3 & Build AI-powered tools"

    def skills(self):
        return {
            "Languages": ["🐍 Python", "🌐 HTML/CSS", "🟨 JavaScript", "☕ Java", "🦀 Rust (beginner)"],
            "Python Tools": ["🪟 Tkinter", "📦 PyInstaller", "🧰 Requests", "🧪 Pytube", "🖼️ Pillow", "🔍 Regex"],
            "AI Libraries": ["📊 Numpy", "🧮 Pandas", "🎯 scikit-learn (beginner)", "👁️ OpenCV"],
            "Other Tools": ["🖥️ Git", "📝 VS Code", "🐧 Kali Linux", "💿 Pop!_OS"]
        }

    def projects(self):
        return [
            "🎥 YouTube Downloader GUI (Tkinter + Pytube)",
            "🔒 Steganography App (Hide messages in images)",
            "🧠 AI Mini Modules (automation, detection)",
            "🤖 IR Sensor + Motor Logic System (Python-based)"
        ]

    def learning(self):
        return [
            "⚙️ Python OOP & File Systems",
            "📚 Machine Learning Basics",
            "🤖 AI for Automation",
            "🪟 Building GUI/Desktop Apps with Python"
        ]

    def dream(self):
        return "🌟 Build my future with code, and buy my dream car — a BMW M3"

    def connect(self):
        return {
            "Website": self.website,
            "Email": self.email,
            "Message": "💬 Let's connect! If you're self-learning too, we're on the same path 🚀"
        }

# 👇 Run the code of life
if __name__ == "__main__":
    me = Developer()
    print("🚀 Welcome to my GitHub!")
    print(f"Hi, I'm {me.name}, a {me.status} working to become a top-tier {me.role}.\n")
    
    print("🔧 Skills:")
    for category, items in me.skills().items():
        print(f"  {category}: " + ", ".join(items))

    print("\n📁 Projects:")
    for proj in me.projects():
        print(f"  - {proj}")

    print("\n📚 Currently Learning:")
    for topic in me.learning():
        print(f"  - {topic}")

    print(f"\n💭 Dream: {me.dream()}")

    print("\n📫 Connect with me:")
    for k, v in me.connect().items():
        print(f"  {k}: {v}")

    print("\n💡 Remember: \"You don't need a degree to build your dream — just discipline, internet, and grit.\"")
