echo "# gradle_multiproject_structure_repo" >> README.md

https://www.petrikainulainen.net/programming/gradle/getting-started-with-gradle-creating-a-multi-project-build/

mkdir core
mkdir app

mkdir core\src\main\java
mkdir core\src\test\java

mkdir app\src\main\java
mkdir app\src\test\java

mkdir springbootapp
mkdir springbootapp\src\main\java\com\chahar\springbootapp\
mkdir springbootapp\src\main\resources

From root project:
    gradle bootRun -pspringbootapp

from Subproject:
    gradle bootRun

References:
https://www.petrikainulainen.net/programming/gradle/getting-started-with-gradle-creating-a-multi-project-build/
