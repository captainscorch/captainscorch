# Hi there, I'm Daniel ✌️

<p><em>Design Engineer & Co-Founder of <a href="https://unlimited.studio">unlimited.studio</em></p>

[![Twitter](https://img.shields.io/twitter/follow/captainscorch?label=Follow)](https://x.com/intent/follow?screen_name=captainscorch)
[![Linkedin](https://img.shields.io/badge/Follow-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/daniel-schmier-6a2557149/)](https://www.linkedin.com/in/daniel-schmier-6a2557149/)
![GitHub](https://img.shields.io/github/followers/captainscorch?label=Follow&style=social)
[![Website](https://img.shields.io/badge/Website-2ab193.svg?&style=flat-square&logo=Google-Chrome&logoColor=white&link=https://captainscor.ch)](https://captainscor.ch)

### 📃 About me

A self-taught creative with expertise in digital media and communication, my passion lies in web development and graphic design, while photography has been a long-standing interest that has inspired me for years.

### 💻 Some more details

```javascript
// 01 LANGUAGES
const languages = ["German (native)", "Englisch (professional – C2)"];

// 02 CODE LANGUAGES
const codeLanguages = ["HTML", "CSS", "JavaScript", "PHP", "Liquid"];

// 03 TECHNOLOGIES
const technologies = {
  // Backend
  backend: {
    php: [
      "Laravel",
      "Livewire",
      "Filament",
      "Nova",
      "Jetstream",
      "Cashier",
      "Spark",
      "Inertia"
    ],
    js: ["Nuxt"],
    shopify: ["Liquid", "Hydrogen", "Oxygen"],
  },

  // Frontend
  frontend: {
    js: ["Vue.js", "Alpine.js"],
    css: ["Tailwind", "Bootstrap"],
  },

  // Dev Ops
  devOps: [
    "CLI",
    "Git",
    "CI/CD",
    "AWS",
    "Docker",
    "S3",
    "EC2",
    "Nginx",
    "Node.js",
    "Envoyer",
    "Forge"
  ],

  // Databases
  databases: ["MySQL", "SQLite", "GraphQL"],

  // Misc
  misc: [
    "Homebrew",
    "Prompt Engineering",
    "Agents",
    "MCP",
    "Cursor",
    "OpenAI API"
  ]
};

// 04 DESIGN TOOLS
const designTools = [
  "Figma",
  "Adobe CC",
  "Photoshop",
  "Illustrator",
  "InDesign",
  "After Effects",
  "Premiere Pro"
];

// 05 ANALYTICS
analytics: [
  "Google Analytics",
  "Google Tag Manager",
  "Google Search Console",
  "Google Lighthouse",
  "PageSpeed Insights",
  "Conversions API",
  "Microsoft Clarity",
  "Meta Pixel",
  "Hotjar"
],

// 05 OPEN SOURCE CONTRIBUTIONS
const openSourceContributions = [
  {
    project: "Laravel Cashier",
  },
];

// Export everything
export {
  languages,
  codeLanguages,
  technologies,
  designTools,
  analytics,
  openSourceContributions
};
```

### 📊 Couple of stats

<small>
<table>
  <tr>
    <th>Activity</th>
    <th>Count</th>
  </tr>
  <tr>
    <td>Pushed commits</td>
    <td>{{ COMMITS }}</td>
  </tr>
  <tr>
    <td>Opened issues</td>
    <td>{{ ISSUES }}</td>
  </tr>
  <tr>
    <td>Submitted pull requests</td>
    <td>{{ PULL_REQUESTS }}</td>
  </tr>
  <tr>
    <td>Reviewed pull requests</td>
    <td>{{ CODE_REVIEWS }}</td>
  </tr>
  <tr>
    <td>Contributed to public repositories</td>
    <td>{{ REPOSITORIES_CONTRIBUTED_TO }}</td>
  </tr>
  <tr>
    <td>Top 8 most used languages</td>
    <td>{{ LANGUAGE_TEMPLATE_START }} {{LANGUAGE_NAME}} {{ LANGUAGE_TEMPLATE_END }}</td>
  </tr>
  <tr>
    <td>Top 4 most used languages</td>
    <td>{{ LANGUAGE_TEMPLATE_START:max=4 }} {{LANGUAGE_NAME}} {{ LANGUAGE_TEMPLATE_END }}</td>
  </tr>
</table>
</small>
