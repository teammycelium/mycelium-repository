# mycelium-repository

## Usage

### Maven
```xml
<repository>
    <name>mycelium-repository</name>
    <url>https://teammycelium.github.io/mycelium-repository/</url>
</repository>
```

### Gradle
Normal Gradle
```groovy
repositories {
    maven {
        name "mycelium-repository"
        url "https://teammycelium.github.io/mycelium-repository/"
    }
}
```

Gradle Kotlin DSL
```kotlin
import java.net.URI

repositories {
    maven {
        name = "mycelium-repository"
        url = URI("https://teammycelium.github.io/mycelium-repository/")
    }
}
```

### SBT
```scala
resolvers += "mycelium-repository" at "https://teammycelium.github.io/mycelium-repository/"
```
