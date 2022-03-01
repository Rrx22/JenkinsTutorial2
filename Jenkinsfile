pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
