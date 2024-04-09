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
  const DriverInfo = "- 16-year-old amateur \n- Male | He/Him pronouns \nBeen coding since last year";
  const DriverStat = "";
  const DriverLanguages = "";
  const DriverProjects = "";
  const DriverSocials = "";
  
    
    const embed = new ReadmeBuilder()
      .setTitle(`OMG IT IS THE`)
      .setDescription(
        ``
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
