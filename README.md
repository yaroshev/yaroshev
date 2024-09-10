const introduction = {
  name: "Yaroslav",
  profession: "Aspiring Full Stack Developer",
  interests: ["Coding", "AI", "Technology", "Problem Solving"],
  skills: {
    languages: ["JavaScript", "Python", "HTML", "CSS"],
    frameworks: ["Node.js", "React", "Express"],
    tools: ["Git", "Jest", "Docker"]
  },
  goals: {
    shortTerm: "Land a Junior Full Stack Developer role",
    longTerm: "Contribute to impactful tech projects and advance in AI"
  },
  greet: function() {
    console.log(`Hi, I'm ${this.name}! I'm an ${this.profession} with a passion for ${this.interests.join(", ")}.`);
  }
};

introduction.greet();
