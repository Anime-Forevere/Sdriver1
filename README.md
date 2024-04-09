```javascript
const { WhoisDriver, DriverStats } = require("Sdriver1.js")
const { SdriverRepos } = require("Sdriver1.github")
const { ReadmeBuilder, ReadmeContentBuilder } = require("Github.js")

module.exports = {
  data: new ReadmeContentBuilder()
    .setName("Driver")
    .setDescription(
      "Info on Sdriver1"
    ),

  async execute(interaction, client) {
    const embed = new ReadmeBuilder()
      .setTitle(`OMG IT IS THE`)
      .setDescription(
        `Hello, I am Sdriver1 or Driver for short. I am a 16-year-old amateur developer and Junior in High School. I am Male and use He/Him pronouns. I mainly focus on Discord bot development and own a verified bot. I code in JavaScript and HTML & CSS. I am learning Python and Java. I am mostly active on Discord if you want to contact me. `
      )
      .setColor(0xff00ae);
    await interaction.reply({ embeds: [embed] });
  },
};

```
`
## Projects
- [Pridebot](https://github.com/Sdriver/Pridebot)
- [Pridebot Website](https://github.com/Sdriver/Pridebot-Website)

## My Stats
![](https://github-readme-stats.vercel.app/api?username=Sdriver1&show_icons=true&theme=dark)
