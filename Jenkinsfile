pipeline {
    agent any
    tools {
        maven "maven-3.9.9"
    }
    stages {
      stage("INIT") {
        steps {
            echo "INIT"
	    echo "CHECKOUT GIT STAGE"
        }
      }
      stage("PACKAGE") {
        steps {
            echo "PACKAGE"
            sh "mvn package"
            sh "ls -a"
        }
      }
      stage("PUSH") {
	echo "PUSH TO DOCKER STAGE"
	echo "PUSH TO DOCKER STAGE"
      }
    }
}
