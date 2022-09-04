```java
public class bixDev extends Developer {
  public bixDev(){
    super("bixgamer707", "Colombia", null);
    init();
  }
  
  public void init(){
    addExperiences(
      "Spigot API", 
      "Configurator", 
      "Setups Creator",
      "Texture Pack Creator",
      "Bungee API"
    );
  }

public abstract class Developer {

  @Getter private final String nickname;
  @Getter private final String country;
  @Getter private final int age;

  private final Set<String> languages = new HashSet<>();
  private final Set<String> experiences = new HashSet<>();

  public GitHubUser(
      String nickname, 
      String country, 
      int age
      
  ) {
  
      this.nickname = nickname;
      this.country = country;
      this.age = age;
  }

  public void addLanguage(
      String... language
  ) {
      this.languages.addAll(language);
  }
  
  public void addExperiences(
      String... experience
  ) {
      this.experiences.addAll(experience);
  }
}
```



> GITHUB STATS

![bixDev GitHub Stats](https://github-readme-stats.vercel.app/api?username=bixgamer707&show_icons=true&theme=radical)

> WAKATIME STATS

[![bixDev Wakatime Stats](https://github-readme-stats.vercel.app/api/wakatime?username=bixgamer707&show_icons=true&theme=radical)](https://github.com/anuraghazra/github-readme-stats)
