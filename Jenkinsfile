pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'pwd'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                sh 'pwd'
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
