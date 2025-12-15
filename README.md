## Jenkins Pipeline Demo

Simple Java Maven project with a Jenkins Pipeline that:
- checks out the repo
- runs Maven tests
- publishes JUnit test results
- Jenkins-Pipeline-Demo

## Structure
```bash

├── src
│   ├── main
│   │   └── java
│   │       └── demo
│   │           └── Calculator
│   └── test
│       └── java
│           └── demo
│               └── CalculatorTest
├── Jenkinsfile
├── pom.xml
├── mvnw / mvnw.cmd
├── target
└── README.md


## Run locally
```bash
mvn test



