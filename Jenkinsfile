pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'pwsh --version'
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
