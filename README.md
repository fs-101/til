# til
1. What is the difference between IDE and text editor?
IDE(Integrated Development Environment)
IDE is a software application that provides the feature of software development to programmers.This can be used as a text editor but since it provides important features like compiling ,debugging etc these are considered heavy and are not opted for simple text modification purpose.
Some common IDE’s available are IntelliJ IDEA, Net-beans and Eclipse
Text Editors
Text editors on the other hand are light weight application software which are used for modification of text files.
Some common Text Editors available are Notepad and Visual Studio Code
2. What are the features of Intellij over Eclipse?
Eclipse community is declining at a high rate where as intellij community is still growing, hence for any kind of issue ,there is a high chance of getting a solution for intellij as compared to eclipse in coming future.
There are few important points due to which intellij is way better than eclipse
Debugging
Debugging or evaluating expression is simple and fast in intellij with just mouse hover action on the required code .
Autocomplete
Intellij IDE being one of the most intelligent IDE provides the feature of autocomplete which is again very fast and increases the rate to completion of code.
3. Why do we use Maven?
Maven is a software project management and build automation tool generally used in java projects.
Main feature of maven:
Manage dependencies easily
Maven has a POM.xml file which has all the dependencies listed in XML format along with the version of the library or dependency. If a new version of library is released we can just change the version value in POM.xml file and the required download and changes are auto imported.
Maven uses the concept of two repositories, first is the central repository and a local repository in userprofile\.m2 folder.Hence all the jars gets downloaded to this .m2 folder.
4. What is the difference between git and github?
Git is a version control system or a source code management tool where as github is a service which hosts git over cloud.Git is locally installed and generally command prompt is used to interact with git whereas to access github we need a web browser interface.
5. What is the difference between git pull and git pull request?
Git Pull
Git pull is a git bash command used to take update from remote repository to local repository.In case any file is missing from the local repository we can execute the pull command and the required files.
git pull
Git Pull Request
Pull request is a feature of git used during collaborative kind of development , it tells other team members about the changes done in a branch before the changes are merged in the base or master branch.
6. What is the importance of .gitignore file?
When a project is developed using some IDE there are configuration files which are not required to be updated in local or remote repositories.To avoid such files to be listed during git add command, git uses the .gitignore file containing extension of files to be excluded.
Hence git will ignore the files whose extension are mentioned in the gitignore file.
7. Why should we prefer mvnw command over mvn command in maven?
8. What is the importance of Readme.md file in GitHub repository?
README.md is a markdown file which contains information about the contents of the repository. This is maintained by the repository owner and developers working on the repository containing project files.
Anyone can get the basic idea of usage and features of the project by reading the readme.md file.
9. How to add a remote repository in local repository?
git remote add origin “SSH-Key_used_for_cloning”
