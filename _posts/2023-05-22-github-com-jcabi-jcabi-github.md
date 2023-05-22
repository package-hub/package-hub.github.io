---
title: jcabi-github
categories: ['java', 'github', 'api']
---
## [jcabi-github](https://github.com/jcabi/jcabi-github)

### Java Object-Oriented Wrapper of GitHub API, with a fake implementation of the entire GitHub API (for your tests)


By default, the library works with Github's API (https://api.github.com)

```java
import com.jcabi.github.*;
public class Main {
  public static void main(String[] args) throws IOException {
    Github github = new RtGithub(".. your OAuth token ..");
    Repo repo = github.repos().get(
        new Coordinates.Simple("octocat/Hello-World")
    );
    Issue issue = repo.issues().create("Test title", "Test description");
    issue.comments().post("My first comment!");
  }
}
```
