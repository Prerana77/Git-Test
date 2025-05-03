"Softcraft Day 2" 

Advantages of Maven
• Maven provides a standard project structure, so all developers can understand the layout of any Maven-based project easily.
• It automates the build process, allowing you to compile, test, and package your code with simple commands.
• Maven handles dependency management, so you don’t have to manually download and add libraries (JAR files) to your project.
• You can control the version of each dependency, and easily update or change them in one place using the pom.xml file.
• Maven has a huge ecosystem of plugins that can help with testing, compiling, reporting, deploying, and more.
• It integrates well with other tools like Jenkins (CI), IDEs like IntelliJ/Eclipse, Docker, and GitHub.
• Since everyone uses the same pom.xml file, team collaboration becomes easier and builds are consistent across different machines.
• The pom.xml acts as documentation for how the project is built and what dependencies it needs.
• Maven supports automated testing, so unit tests can run as part of the build process using tools like JUnit.
• It also supports multi-module projects, making it easier to manage large applications split into smaller, related modules.

How it Works
• You create a project with a pom.xml file that lists dependencies and build settings.
• When you run a Maven command like mvn compile, Maven reads pom.xml.
• It downloads needed libraries from the internet (Maven Central).
• Maven compiles, tests, and packages your project automatically.
• The final output (like a .jar file) is stored in the target/ folder.
