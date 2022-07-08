# StructureLib

1. Add this to your build.gradle
    ```groovy
    dependencies {
      compile "com.github.SpaceAccident:StructureLib:master-SNAPSHOT:deobf"
    }
    repositories {
        maven {
            name = "jitpack.io"
            url = "https://jitpack.io"
        }
    }
    ```
   Replace `master-SNAPSHOT` with a commit hash or a tag name (if any) of your choice to prevent unexpected upstream changes.
2. Add `required-after:structurelib;` to your `@Mod(dependencies = "..")` tring.
3. Add `structurelib` to your `mcmod.info`.

