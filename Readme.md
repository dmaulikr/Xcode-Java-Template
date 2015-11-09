#Xcode Java Template

This is a bundle of files usefull for developing Java in Xcode.
The first is an Xcode project that has been setup to build, run and archive Java code using an install of the JDK.
The second is a file template for an empty java class.
Both can be used independently from each other.

##To use the project file
1. Copy the folder "Java Project" "and rename it and it's subfolder to whatever you want to call your project.
2. Open "Java Project.xcodeproj" and slowly click the project name on the left to rename the project file, and accept Xcode's suggestion what other things need to be renamed.
3. Start coding, but make sure to use the main function inside the Main.java file to start you programm.
You can now
- **Build** to compile the .java Files into .class Files
- **Run** to compile the .java files and run the project
- **Archive** to create a .jar from your project

##To use the file template
1. Copy the Folder "Javafile.xctempalte" to "~/Library/Developer/Xcode/Templates" (Tip: use cmd+shift+G inside Finder to go to a folder).
2. Inside Xcode create a new file (cmd+N), select "Template" from the left and then select "Java Class".
3. The filename you choose will automatically be set as the class name and in the initializer method

##Other Tips
To create custom code snippets (e.g. to quickly access "System.out.println("")") just write the desired content of your snippet anywhere inside the code editor, then drag it into the snipped collection in the lower right and finally right click the new snippet at the bottom of the list and enter a name and a shortcut (e.g. "sysout")

*By Hendrik Noeller, project setup partly from [https://www.youtube.com/watch?v=CmbdOfYNc3g](https://www.youtube.com/watch?v=CmbdOfYNc3g)*