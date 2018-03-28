# sonar-iris-java-plugin

Java code rules 魔改 for iris project. Can be used in SonarQube.

This plugin combines PMD rules and P3C rules.For PMD, check https://github.com/SonarQubeCommunity/sonar-pmd. For P3C, check https://github.com/alibaba/p3c

# Install 
## 1.Package jar
1. git clone https://github.com/yellowb/java-code-standard-sonar-plugin.git
2. mvn clean & mvn package

## 2.Download sonarqube and install
Visit SonarQube website.

## 3.Install puglin
1. put generate sonar-pmd-plugin-2.6.jar into <SONARQUBE_FOLDER>\extensions\plugins
2. restart SonarQube
