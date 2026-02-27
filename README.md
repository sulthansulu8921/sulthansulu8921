## 👋 Hi GUYS

```
class SulthanShafeer {
  constructor() {
    this.name = "Sulthan Shafeer";
    this.alias = ["Sulthan", "Full Stack Developer 💻🔥"];
    this.role = "Full Stack Developer (React + Python Django) 🚀";
    this.location = "Calicut, Kerala, India 🌴";
    this.skills = [
      "HTML",
      "CSS",
      "JavaScript",
      "TypeScript",
      "React",
      "Bootstrap",
      "Python",
      "Django",
      "Flask",
      "PostgreSQL",
      "Firebase",
      "Supabase",
      "Git",
      "GitHub"
    ];
    this.learning = [
      "Advanced React",
      "TypeScript Deep Dive",
      "System Design",
      "Software Testing",
      "Clean Code"
    ];
    this.motto = "Eat(), Sleep(), Code(), Repeat();";
  }

  introduce() {
    console.log(`👋 Hi, I'm ${this.name}, also known as ${this.alias[1]}.`);
    console.log(`📍 Location: ${this.location}`);
    console.log(`💼 Role: ${this.role}`);
    console.log(`🧠 Tech Stack: ${this.skills.join(", ")}`);
    console.log(`📚 Currently Learning: ${this.learning.join(", ")}`);
    console.log(`💡 Motto: "${this.motto}"`);
    console.log("☕ Fun Fact: I build projects while debugging real-world problems!");
  }

  currentStatus() {
    console.log("🟢 Status: Building real projects and improving every day 🚀");
  }

  futureGoal() {
    console.log("🚀 Goal: To become a professional developer and work in Dubai 🇦🇪");
  }
}

const me = new SulthanShafeer();
me.introduce();
me.currentStatus();
me.futureGoal();
