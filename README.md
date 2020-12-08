```java
public class GekkeGlenn extends GitHubUser {

  public GekkeGlenn() {
    super("GekkeGlenn", "Netherlands");

    this.addTopLanguages("PHP", "Java")
    this.addLanguage("html", "css", "javascript", "nodejs");
    this.AddFrameWorks("Laravel", "Tailwindcss");
  }
}

public abstract class GitHubUser {

  private final String name;
  private final String country;

  private ArrayList<String> topLanguages = new ArrayList<>();
  private ArrayList<String> languages = new ArrayList<>();
  private ArrayList<String> frameWorks = new ArrayList<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addTopLanguages(String... topLanguages) {
    this.topLanguages.addAll(topLanguages);
  }

  public void addLanguage(String... language) {
    this.languages.addAll(language);
  }

  public void addFrameWorks(String... frameWorks) {
    this.frameWorks.addAll(frameWorks);
  }
}
```
<table>
  <tr>
    <td>
      <a href="https://github.com/anuraghazra/github-readme-stats">
        <img align="center" src="https://github-readme-stats.vercel.app/api/wakatime?username=GekkeGlennDev&layout=compact" />
      </a>
    </td>
    <td>
      <img src="https://wakatime.com/share/@af07fbf9-4b8e-424e-bdec-8fade491e4d4/47d48645-0068-42fe-b983-9f57c92f3ef3.svg" alt="wakatime stats" height=195>
    </td>
  </tr>
  <tr>
    <td colspan=2>
      <img src="https://github-readme-stats.vercel.app/api?username=GekkeGlenn-Dev&count_private=true&show_icons=true&theme=dark&hide_border=false" alt="github stats">
    </td>
  </tr>
</table>

<!--
**GekkeGlenn-Dev/GekkeGlenn-Dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
