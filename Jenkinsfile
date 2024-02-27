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
                sh "sudo su"
                sh "chmod +x src/Classes/HelloWorld.java && chmod +x src/Classes/HelloWorld.class"
                sh "cp src/Classes/. /var/jenkins_home/workspace/HelloWorld"
                sh "cd /var/jenkins_home/workspace/HelloWorld"
                sh "whoami"
                sh "pwd"
                sh "ls"
                sh "javac HelloWorld.java"
                sh "ls"
                sh "java Helloworld"
            }
        }
    }
}
