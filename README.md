<!-- <a href="https://kimberlycasamina.onrender.com/" >
<img alt="portfolio" title="Portfolio" src="https://img.shields.io/badge/Website-kimberlycasamina-orange?logo=aboutdotme"/>
</a>

<a href="https://kimberlycasamina.onrender.com/">
    <img alt="email" title="Email" src="https://img.shields.io/badge/Email-kimi.casamina@gmail.com-green?logo=gmail"/>
</a>

<br>

---

<br>
# ABOUT ME -->

```javascript
const about_me = {
  name: "Kimberly Casamina",
  email: "kimi.casamina@gmail.com",
  portfolio: "kimberlycasamina.onrender.com/",
  attributes: {
    sobriety: 50,
    hunger: 50,
    cleanliness: 50,
    eat: function () {
      const modifier = 3.5;
      this.hunger -= modifier;
      return `Hunger is decreased by ${modifier}`;
    },
    shower: function () {
      const modifier = 3.5;
      this.hunger += modifier;
      return `Cleanliness is increased by ${modifier}`;
    },
    sleep_on_the_sofa: function () {
      const modifier = 3.5;
      this.sobriety += modifier;
      return `Sobriety is increased by ${modifier}`;
    },
  },
  whats_in_my_bag: [
    {
      shirts: {
        description: "plain and graphic tees folded in a marie kondo way",
        quantity: 5,
        quality: "very clean",
        brand: ["bench"],
      },
    },
    {
      pants: {
        description: "washed out jeans",
        quantity: 4,
        quality: "ok",
        brand: ["zara"],
      },
    },
    {
      shoes: {
        description: "plain white shoes",
        quantity: 1,
        quality: "still kicking",
        brand: ["puma"],
      },
    },
    {
      laptop: {
        description:
          "small, portable, 11 inches laptop powered by intel quad core with a 2.4 ghz clock speed and 4 gb of ram",
        quantity: 1,
        quality: "good",
        brand: ["acer"],
      },
    },
  ],
  list_of_activities: [
    "sitting on the bus",
    "sitting on the sofa bed",
    "shower",
  ],
  education: ["Self-taught Developer", "Associate in Computer Technology"],
  career_history: ["Frontend Developer"],
  skills: {
    preffered_stack: [
      "html",
      "css",
      "javascript",
      "react",
      "tailwindcss",
      "sass",
      "nodejs",
      "mongoose",
      "express",
      "mongodb",
    ],
    can_use: ["php", "laravel", "mysql", "postgresql", "python", "django", "nextjs", "graphql", "jest"],
    dev_tools: [
      "git",
      "github",
      "vscode",
      "postman",
      "npm",
      "bash",
      "composer",
      "vite",
      "pip",
      "figma",
    ],
    others: [
      "Data Structures & Algorithms",
      "RESTful API",
      "Responsive Web Design",
      "Database Design",
      "Third-party services Integration",
      "Authentication & Authorization",
      "Encryption & Data Security",
    ],
  },
};
```
