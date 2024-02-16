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
                
                sh "whoami"
            }
        }
        stage('Deploy') {
            steps {
                sh 'java src.Classes.HelloWorld'
            }
            
        }
    }
}
