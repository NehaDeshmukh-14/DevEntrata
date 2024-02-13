![Screenshot 2024-02-11 224131](https://github.com/NehaDeshmukh-14/DevEntrata/assets/156272537/4495351b-36e2-4734-b64a-802df1a64a78)Java Maven TestNG Automation Starter
This is a simple project that would allow anyone to get up and running with Java, Maven, Selenium and TestNG. It also explains how to execute a simple test that will assert the web-elements of a page.
Currently the project has four test that will navigate to https://www.entrata.com/ .

Table of Contents
There are a few things we need before running the tests. These are:
Check your system to see if you have the latest Java version installed.
Command:
$ java -version
If you do not have the latest Java installed, find out how to install Java here.
Ensure your JAVA_HOME environment to the location of the installed JDK. Find out how to do that here.

Setting up Eclipse
Navigate to the Eclipse download page and download eclipse for Java EE developers.
Installing TestNG
1.Installing a Plugin:
oInside Eclipse, click on the Help menu
oSelect Install New Software.
2. Locating the Plugin:
Click the Add button
Enter http://beust.com/eclipse in the Location field
3.Selecting the Plugin:
Ensure the TestNG checkbox is selected
Click the "Next" button to the right bottom
4. Finishing up:
Accept the terms of the license agreement
Click on the Finish button

Setting up Maven
1.Download Maven here.
2.Unzip the distribution archive to the directory you wish to install Maven. I extracted maven to folder
3.Add Maven to the PATH. 
4.Verify Maven was correctly installed
oCommand:    mvn –version

Maven dependencies are crucial to running any Maven project. Maven dependencies contains key references to libraries that a Maven project needs to execute. The pom.xml in the root of a Maven project file stores the dependencies for a project.
Running the Project
From Eclipse
1.Import this project into Eclispe
2.Right click the project then select Run As then Maven Tests
Following the above steps executes the configurations found in the testing.xml file by default.

From the Command Line
Navigate to the location of project then execute mvn compile.
Expected output:
![Screenshot 2024-02-11 230321](https://github.com/NehaDeshmukh-14/DevEntrata/assets/156272537/53c28f76-c5b5-43cb-9df6-689a2ef9426f)
![Screenshot 2024-02-11 223811](https://github.com/NehaDeshmukh-14/DevEntrata/assets/156272537/0ce8bb25-cf4a-4619-90ac-253af83db331)



Navigate to the location of project then execute mvn test.
Expected output:
![Screenshot 2024-02-11 223947](https://github.com/NehaDeshmukh-14/DevEntrata/assets/156272537/a48a6e9a-659c-4797-831f-bf1deb6fd521)


Navigate to the location of project then execute mvn install.
Expected output:
![Screenshot 2024-02-11 224131](https://github.com/NehaDeshmukh-14/DevEntrata/assets/156272537/e95d2533-78f5-498a-92d5-7dd43ee74cb5)
