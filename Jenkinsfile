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
            steps {
                sh "chmod +x src/Classes/HelloWorld.java && chmod +x src/Classes/HelloWorld.class"
                sh "whoami"
                sh "pwd"
                sh "ls"
                sh "javac src/Classes/HelloWorld.java"
                sh "ls"
                sh "java src.Classes.Helloworld"
            }
        }
    }
}
