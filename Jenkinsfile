pipeline {
    agent any
    
    tools {
        maven 'mvn' 
      }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    
        stage('Run unit tests') {
            steps {
                sh 'mvn clean install'
            }
        }

    }
}
