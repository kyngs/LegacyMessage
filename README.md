# LegacyMessage
A simple util to translate legacy color codes in Minecraft, to MiniMessage compatible ones.

# How to use
[Obtain the dependency from jitpack.](https://jitpack.io/#kyngs/LegacyMessage/) 

Example:

```java
import xyz.kyngs.utils.legacymessage.LegacyMessage;

/**
 * An example which takes a provided (legacy) string,
 * and converts it to a MiniMessage compatible one.
 */
public class Test {
    public static void main(String[] args) {
        if (args.length <= 0) return;

        /*
         * Convert the provided string and print it
         */
        System.out.println(LegacyMessage.fromLegacy(String.join(" ", args)));

    }
}
```
