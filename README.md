```java
public class GekkeGlenn extends GitHubUser {

  public GekkeGlenn() {
    super("GekkeGlenn", "Netherlands");

    this.addLanguage("Java", "C#", "Javascript", "c++", "html", "css");
  }
}

public abstract class GitHubUser {

  private final String name;
  private final String country;

  private ArrayList<String> languages = new ArrayList<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addLanguage(String... language) {
    languages.addAll(language);
  }
}
```
<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=GekkeGlenn-Dev&count_private=true&show_icons=true&theme=dark&hide_border=false" alt="github stats">
    </td>
    <td>
      <img src="https://wakatime.com/share/@e837145a-31e5-48fd-ae85-70bcf7426b10/204c36fb-8fa9-46c3-ae0d-4a8dbbee943d.svg" alt="wakatime stats" height=195>
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
