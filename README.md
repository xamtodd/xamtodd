```java
import java.util.ArrayList;

public class Profile {
    private String name;
    private ArrayList<Language> languages = new ArrayList<>();
    private String operatingSystem;
    
    public Profile(){
        this.name = "xamtodd";

        languages.add(new Language("java"));
        languages.add(new Language("C"));
        languages.add(new Language("SQL"));
        languages.add(new Language("PHP"));
        languages.add(new Language("HTML"));
        languages.add(new Language("CSS"));

        this.operatingSystem = "MacOS";
    }
}
```