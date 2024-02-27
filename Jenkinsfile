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
                sh "cd ./src/Classes"
                sh "ls"
                sh "javac HelloWorld.java"
                sh "ls"
                sh "java Helloworld"
            }
        }
    }
}
