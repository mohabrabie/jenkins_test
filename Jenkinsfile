pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh docker
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