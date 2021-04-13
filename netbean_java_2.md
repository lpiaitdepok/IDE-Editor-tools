# Developing General Java Applications
## Project Setup
- Creating a Java Class Library Project
  To open a new Java project, press:
Windows™/Linux: Ctrl+Shift+N
- Creating a Java Application Project
- Configuring the Compilation Classpath
  - To add the library’s utility classes to the project classpath:
  - In the **Projects** window, right-click the **Libraries** node for the MyApp project and choose **Add Project…** as shown in the image below.

![addproj]()

If necessary, in the **Add Project** window browse to NetBeansProjects and, select the MyLib project folder. When you do so, you will see Project Name: MyLib and, Project JAR Files: dist/MyLib.jar can be added to the project.

Notice that a JAR file is shown for MyLib even though you have not actually built one yet. This JAR file will get built when you build and run the MyApp project.

Select Add Project JAR Files then expand the Libraries node of MyApp in the Projects window and, you will see that MyLib project’s JAR file has been added to the MyApp project’s classpath.

- Creating and Editing Java Source Code
- Creating a Java Package and Class File
- Creating a Java Package and Class File
In the **Projects** window, right-click the MyLib project node and select **New** > **Java Class…**. Alternatively, regardless of where you are in the project, press:

Windows™/Linux: Ctrl+N

macOS™: Command+N
 

- Editing a Java File
- Compiling and Running the Application
- Setting the Main Class and Execution Arguments
- Running the Application
- Testing and Debugging the Application
- Creating JUnit Tests
- Running JUnit Tests
- Debugging the Application
- Building, Running, and Distributing the Application
- Building the Application
- Running the Application Outside of the IDE
- Distributing the Application to Other Users
- Other Common Tasks
- Making the Javadoc Available in the IDE
- Generating Javadoc for a Project
