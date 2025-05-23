pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning repository...'
                git 'https://github.com/hbin1911/Assign.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Running build step...'
                sh 'javac Hello.java'
            }
        }
        stage('Run') {
            steps {
                echo 'Running program...'
                sh 'java Hello'
            }
        }
    }
}
