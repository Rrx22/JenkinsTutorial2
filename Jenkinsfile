pipeline {
    agent any
    
    tools {
        maven 'maven 3.8.4' 
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
