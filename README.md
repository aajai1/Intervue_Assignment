**📕README - Intervue.io Automation Testing**

This project is an automated test suite for the Intervue.io web application using Selenium WebDriver with TestNG framework. 

In this Test I have Implemented Link, Elements directly in test case because of Single Test but using POM Method is best practise to reuse element and centralizing link in property file.

**Setup Instructions-  Install Prerequisites**

👍 Java JDK 8 or above

👍	Maven (if using pom.xml)

👍	Chrome Browser

**Project Dependencies**

**🤖To Automate Webpage – Selenium Dependency**

<dependency>
	
    <groupId>org.seleniumhq.selenium</groupId>
		
    <artifactId>selenium-java</artifactId>
		
    <version>4.31.0</version>
		
</dependency>

**🤖	To Manage test case – TestNG Dependency**

<dependency>
	
    <groupId>org.testng</groupId>
		
    <artifactId>testng</artifactId>
		
    <version>7.11.0</version>
		
    <scope>test</scope>
		
</dependency>


**🤖	To Handle Files – Apache Common POI**

<!-- https://mvnrepository.com/artifact/org.apache.poi/poi -->
<dependency>
	
    <groupId>org.apache.poi</groupId>
		
    <artifactId>poi</artifactId>
		
    <version>5.4.1</version>
		
</dependency>


**How to Run - Using TestNG :**

▶️	Right-click on the Login.java file > Run As > TestNG Test


**Test Scenarios :**

1️⃣ Open Homepage → Click "Login" on the Homepage

2️⃣	Switch Tabs → Click "Login" for Companies on second tab

3️⃣	Enter Login Credentials

4️⃣	If Login fails Screenshot is captured.

5️⃣	If Login Passed Opens Search Modal 

6️⃣	Search for a name (e.g., "Ajai") and click result

7️⃣	Logout from the Profile

**🌂After Execution :**

The browser will automatically close after the suite completes via the @AfterSuite block.



