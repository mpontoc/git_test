# git_test 

Commands of Maven Cucumber Java

Running a Class Specificated
-Dtest=Runner test 
Runner is the name of class Runner.java

Overwired the runner tag
mvn -Dcucumber.options="--tags @Test" test

Rerun
-Dtest=ReRun -DfailIfNoTests=false -Dsurefire.rerunFailingTestsCount=2 test
