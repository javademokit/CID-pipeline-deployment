pipeline {

    agent any
    tools {
        maven 'Maven_3.5.2' 
    }
    stages {
        stage('Compile stage') {
            steps {
                bat "mvn clean compile" 
        }
    }

         stage('testing stage') {
             steps {
                bat "mvn test"
        }
    }

         stage('run stage') {
             steps {
                bat "mvn spring-boot:run"
        }
    }
        

  }

}
