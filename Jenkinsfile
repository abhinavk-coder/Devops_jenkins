pipeline {
    agent any
    environment {
        JAVA_HOME = 'C:/Program Files/jdk-21.0.2/bin'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                bat "cd C:/Program Files/jdk-21.0.2/bin  && mkdir abhinav.txt"
            }
        }
    }
}
