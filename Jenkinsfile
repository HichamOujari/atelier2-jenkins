pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                eval 'mvn clean'
            }
        }
        stage('Test') {
            steps {
                eval 'mvn test'
            }
        }
        stage('Package') {
            steps {
                eval 'mvn package'
            }
        }
    }
}