# Appium-demo
Building appium skeleton /framework from sratch

## Prerequisites
1. Java JDK
2. Appium is installed
3. Android SDK is setup
4. XCode is setup (for testing on IOS)
5. Mobile device is ready for automation
6. Eclipse is installed


## Dependencies
1. https://mvnrepository.com/artifact/io.appium/java-client
2. https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java
3. https://mvnrepository.com/artifact/org.testng/testng

## Steps

1. Install TestNG in eclipse
2. Create Maven project
3. Add dependencies (appium java client, selenium java, and TestNG)
4. Save -> Build -> Clean Project
5. Create two packages src/test/java (test & pages)
6. User src/test/resources create a folder apps (keep .apk, .ipa, or .app)
7. Inside the tests folder create java class (file name BaseClass.java). 
8. Create setup() & tearDown() method along with with @BeforeTest and @AfterTest annotation