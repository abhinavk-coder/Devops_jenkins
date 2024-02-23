pipeline {
    agent any
    environment {
        JAVA_HOME = 'C:/Program Files/jdk-21.0.2/bin'
    }

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
                bat"cd C:"
                bat"pwd"
                bat"cd Users/Abhinav/AppData/Local/Jenkins/.jenkins/workspace/"
                bat "copy HelloWorld 'C:/Program Files/jdk-21.0.2/bin/' && cd C:/Program Files/jdk-21.0.2/bin/HelloWorld && javac src/Classes/HelloWorld.java && java src.Classes.Helloworld"
            }
        }

    }
}
