pipeline {
    agent any
    stages {
        stage ('Clean') {
            steps {
               cmd_exec(' mvn clean')
            }
        }

        stage ('Test') {
            steps {
                cmd_exec('mvn test')
            }
        }

         stage ('Package') {
                    steps {
                        cmd_exec('mvn package')
                    }
              }
    }
}