pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sleep(10)
                sh 'pwd'
                sleep(15)
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
