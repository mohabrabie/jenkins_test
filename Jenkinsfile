pipeline {
    agent any

    stages {
        stage('Build') {
            // build
            steps {
                // sh docker build .
                sh "build the image"
            }
            // run
            steps {
                // sh docker run 
                sh "run the container here"
            }
        }
        stage('test') {
            steps {
                sh 'testing the application here'
            }
        }
        stage('deploy') {
            steps {
                sh "deploying the application here"
            }
        }
    }
}