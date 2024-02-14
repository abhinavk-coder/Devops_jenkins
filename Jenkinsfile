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
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            
                sh "javac src/Classes/HelloWorld.java && java src.Classes.Helloworld"
            
        }
    }
}
