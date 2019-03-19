# Developer-Documentation

## Initial Project Setup for Development Environment
1. Ensure you have:
    * IntelliJ IDEA Ultimate 2018
    * Java 8u202
    * Apache Derby 10.14.2.0
      * Installed in `/jdk1.8.0_202/db/`
2. Import the project into IntelliJ as an **existing gradle project**
    * Make sure to select the options for **Use auto-import** and **User gradle ‘wrapper’ task configuration**
3. You should now be able to run the gradle task **application -> run**
    * If you get an error that says `Java DB Driver not found. Add the classpath to your module`, follow the steps that get printed to the console to add the Apache Derby library to the project.
