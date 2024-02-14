pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sleep(10)
                sleep(15)
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                sh 'ls -la'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Deploy') {
            steps {
                sh 'java src.Classes.HelloWorld'
            }
            
        }
    }
}
