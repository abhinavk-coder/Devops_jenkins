pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                sh 'javac src/Classes/HelloWorld.java'
            }
        }
        stage('Deploy') {
            steps {
                sh 'java src.Classes.Helloworld'
            }
            
        }
    }
}
