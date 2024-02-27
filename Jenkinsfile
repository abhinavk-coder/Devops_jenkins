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
                sh "ls"
                sh "whoami"
                sh "pwd"
                sh "cd src/Classes"
                sh "ls"
                sh "javac HelloWorld.java"
                sh "ls"
                sh "java Helloworld"
            }
        }
    }
}
