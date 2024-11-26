pipeline {
    agent any
    tools {
        maven "maven-3.9.9"
    }
    stages {
      stage("INIT") {
        steps {
            echo "INIT"
        }
      }
      stage("PACKAGE") {
        steps {
            echo "PACKAGE"
            sh "mvn package"
            sh "ls -a"
        }
      }
    }
}
