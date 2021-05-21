# CST 3613 - Application Development With Java
## Final Project

### How to create a jar for this project:
From your command line interface (CLI) go to the project folder.
<br /> 
e.g. `cd final-project `

### How to run this project:
Make sure you have JavaFX somewhere in your computer. 

Go to the .jar file folder and open your CLI referencing the same folder. (You can also go to the folder using your CLI).

Then proceed to copy and paste the following code into your CLI 
and replace **/path/to/javafx-sdk-15.0.1/lib** with your own JavaFX path. 
Also, make sure you replace **your-jar-file.jar** with the jar you just created.

java --module-path **/path/to/javafx-sdk-15.0.1/lib**
--add-modules javafx.controls,javafx.fxml -jar **your-jar-file.jar**

### Technologies used to build this project:
* Java 16
* Maven
* FXML 
* JavaFX 
* MongoDB

### Disclaimer: