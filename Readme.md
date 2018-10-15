SAMPLE README FILE
==========================
Requirement 1 :
Make a generic Devops pipeline which could be deployed on cloud

Subtask :
1. Write a helloworld api (microservice) and set up a VM locally (nect step is to use container)
2. As soon as the code pushed to the working branch and once code is revievied it should be merged in source control(for simplicity i take it as git)
3. Once Code merge happens( the git webhook should be created and the build pipeline to be trigerred automatically)
4. Again lets say all the steps of bulid to run (clean compile build test - regression test , new unit tests , integration test cases and if need be performance test )
5. Once all the test case are passed , the report to be generated (may be we can plan for rich html report based on feasibilty and suitablity) - ExtentReportGenerator
6. Then the new files or changes (jar, exe, config files etc) to be deployed to the server or Nexus

Later Task:
1.Usage of container like Docker/Vagrant etc
2. After this local set up - how to use Azure instead of local set up

Tools can be used :
Git - source control
Jenkin - automated build
SonarQube + Nexus - Code Repository