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
                
                sh 'cd src/Classes && javac HelloWorld.java'
            }
        }
        stage('Deploy') {
            steps {
                sh 'java src.Classes.HelloWorld'
            }
            
        }
    }
}
