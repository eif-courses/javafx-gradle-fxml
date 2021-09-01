# Java FX project ready for Graphic UI design tool GLUON Scene Builder.
- Requirements download Scene Builder: (https://gluonhq.com/products/scene-builder/).
- Download IntelliJ IDEA or other IDE with integrated Gradle tool or install it locally.
- Clone project and later run this command in terminal ```gradlew clean run``` or ```./gradlew clean run``` if you using gradle wrapper leave w suffix.
# Folder Structure 
- HomeController main Controller class for Home.fxml file.
- Main class entry/driver class for load Home.fxml and custom style.css.
- build.gradle project settings if need more modules used here is place to add it.
- module-info.java some modules for java FX FXML file use and core tools. 
# IMPORTANT 
- When using new Controller class or other FXML files you must add manually controller class to root element in FXML file
  EXAMPLE. ```html <VBox prefHeight="400.0" prefWidth="640.0" xmlns="http://javafx.com/javafx/11.0.1" xmlns:fx="http://javafx.com/fxml/1" fx:controller="eif.viko.lt.javafxgradle.starter.controller.HomeController">```





