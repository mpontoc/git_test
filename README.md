# git_test 

Commands of Maven Cucumber Java

Running a Class Specificated
-Dtest=Runner test 
Runner is the name of class Runner.java

Overwired the runner tag
mvn -Dcucumber.options="--tags @Test" test

Rerun
-Dtest=ReRun -DfailIfNoTests=false -Dsurefire.rerunFailingTestsCount=2 test

Find package activity on android by windows

adb shell dumpsys window windows | findstr <any unique string from your pkg Name>
ex: adb shell dumpsys window windows | findstr calc  


https://medium.com/@ivantay2003/appium-desired-capabilities-basic-cheat-sheet-to-launch-mobile-application-ios-android-75b664367031

adb shell
dumpsys window windows | grep -E 'mCurrentFocus'
dumpsys window windows | grep -E ‘mFocusedApp’


XCUIElementTypeButton 
XCUIElementTypeOther 
XCUIElementTypeStaticText 
XCUIElementTypeWindow 
XCUIElementTypeApplication 
XCUIElementTypeNavigationBar 
XCUIElementTypeTableCell
XCUIElementTypeCell

System.out.println(driver.getPageSource());

https://medium.com/swlh/3-ways-to-find-element-selector-for-ios-app-with-appium-5e44be8bf2c9
