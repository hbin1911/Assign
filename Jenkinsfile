pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'No build step needed for JS. Moving to run...'
            }
        }
        stage('Run JavaScript') {
            steps {
                echo 'Running demo.js using Node.js...'
                bat 'node demo.js'
            }
        }
    }
}
