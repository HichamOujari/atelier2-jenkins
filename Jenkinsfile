pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
               mvn clean
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Package') {
            steps {
                sh 'mvn package'
            }
        }
    }
}