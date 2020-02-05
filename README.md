# JUnit Tests

## Setup

I tried to figure out how to import the JUnit files in to VS Code but it ended up being easier to just do it with Eclipse. If you want to figure it out, go for it. Anyways, here is how you run the JUnit Tests:
1. Create a new Java project in Eclipse
2. Add a new file (eg. Kayak.java) and put your code in there
3. Add a new JUnit test (Right Click > New > J Unit Test Case)
4. Replace the code in that test with the code in the shared tests file
5. If you run into errors, delete module-info.java because [of this stack overflow thread]( https://stackoverflow.com/questions/53033899/must-declare-a-named-package-eclipse-because-this-compilation-unit-is-associated)
6. When you push code back up, just copy paste over the shared test file. Keep directories separate to avoid someone accidentally pasting their real code in.
7. Also... Obviously pull in before you try to push and resolve merge conflicts

Step 3 needs to be done because Eclipse automatically includes the imports.

There is a .gitignore just in case someone messes up...
