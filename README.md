# crafting-interpreters
my attempt at Robert Nystroms book

## working with Java
from the project root, compile all .java files into .class files
```
cd /workspaces/crafting-interpreters
javac -d out lox/com/craftinginterpreters/lox/*.java lox/com/craftinginterpreters/tool/*.java
```
then run the Lox class
```
java -cp out com.craftinginterpreters.lox.Lox
```
to run GenerateAst Class
```
java -cp out com.craftinginterpreters.tool.GenerateAst output_directory
```
