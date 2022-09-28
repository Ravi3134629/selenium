
**Prerequisites for configuring Selenium in Eclipse**:
**Install** JavaDownload Java SE Development Kit 16.0.2 according to the Windows, Linux, or macOS platform being used.

**Source**
**https://www.oracle.com/java/technologies/downloads/#java16**
Run the JDK Installer by double-clicking on the file name in the download location and following the instructions on the instruction wizard. Alternatively, silently install JDK by entering the following command:
**jdk.exe /s**

**Install Eclipse IDE**:
**https://www.eclipse.org/downloads/**
**Install Selenium**:
**https://www.selenium.dev/downloads/**
Download latest version of selenium
Install Selenium to be set up in Eclipse.

**Install Browser Driver**
For Cross Browser Testing, download the relevant Browser Driver – ChromeDriver (for Chrome), GeckoDriver (for Firefox), SafariDriver(for Safari), and InternetExplorerDriver and MSEdgeDriver (IE and Edge respectively). Place these Browser Driver files in a directory that is part of the environment PATH. This will allow a command-line call to the programs to execute them irrespective of the working directory.

**Install Java Language Bindings**
**https://github.com/SeleniumHQ/selenium/releases/download/selenium-3.141.59/selenium-java-3.141.59.zip**

**How to configure Selenium in Eclipse**
Here are the steps to configure Selenium Webdriver with Eclipse:

**Step 1: Launch Eclipse**

To launch Eclipse double click on the eclipse.exe file in the download location.

**Step 2: Create Workspace in Eclipse**
This workspace named “C:\BrowserStack” is like any other folder, which will store all the test scripts. Launch the BrowserStack workspace.

**Step 3: Create New Java Project in the BrowserStack Workspace**

Create a new Java Project by clicking on File > New > Java Project and name it.

**Step 4: Create Package and Class under the Java Project** 

By clicking on the src folder (which is the source folder), create a new package and name it (BrowserStack). Then right-click on the package name and create a class. 
**Step 5: Add Selenium JARs to the Java Project in Eclipse**

To add the Selenium Jars to the BrowserStack Java right click on the BrowserStack Project folder and select the Properties option. In the properties window, click on the Java Build Path and Add External JARs. Browse and add the downloaded Selenium JARs i.e. Client Combined JAR and all the JARs under the Libs folder, then click Apply and Close.

**This configures Selenium with Eclipse, making it ready to execute the first test script.**
