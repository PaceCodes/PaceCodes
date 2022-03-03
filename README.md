<div align="center">

<h1>Hi <img src="images/Hi.gif" width="40px" />, I'm <a href="https://www.github.com/PaceSomesh">Pace</a>!</h1>
</div>

```java
  public class Pace extends Human implements Gamer, Developer {

	@Override
	public String getName() {
		return "Somesh";
	}
	
	@Override
	public List<String> getAliases() {
		return Arrays.asList("Pace", "My Name");
	}

        public Pace() {
        super("Pace", "Earth");

        this.addLanguage("Java", "Python", "Javascript", "Kotlin");
        this.addExperience("3 Years+(java)", "2years+(python)", "6months+(kotlin)", "1 year (js)", "Total 5 years+");
     }
   }

	@Override
	public String aboutme() {
		return "I like to play piano" +
		"\n" + "I like to code Java";
	}
    
	@Override
	public void codingStuff() {
		String[] learning = ["Java", "Kotlin", "ReactJS"];
		String tryingTo = "Make good Android applications & websites";
	}
	
} 


public abstract class Human {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public Human(String username, String placeilive) {
      this.name = username;
      this.country = placeilive;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```

<p align = "center"><img src = "https://github-widgetbox.vercel.app/api/profile?username=PaceCodes&data=followers,repositories,stars,commits"></p>
<p align = "center"><img src = "https://github-widgetbox.vercel.app/api/skills?names=java,kotlin,python,html,css,javascript,dart,c,cpp,csharp&includeNames=true"></p>

<div align="center">
	
[![Pace's GitHub stats](https://github-readme-stats.vercel.app/api?username=PaceCodes&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true)](https://github.com/PaceCodes) 
[![My most used languages](https://github-readme-stats.vercel.app/api/top-langs/?username=PaceCodes&layout=compact&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515&count_private=true&langs_count=6)](https://github.com/PaceCodes)
### Profile Visits 

![Visitors](https://komarev.com/ghpvc/?username=PaceCodes&color=blueviolet)
---

</details>

![My github activity graph](https://activity-graph.herokuapp.com/graph?username=pacecodes&theme=react-dark)

