pipeline {
    agent any
    stages {
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
