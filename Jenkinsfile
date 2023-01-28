pipeline {
    agent any

    stages {
        stage('Build') {
            // build
            steps {
                // run and build the image
                echo "build and run the image here"
                ls
                // sudo docker build .
                // sudo docker run --expose 3000 node:12
            }
        }
        stage('test') {
            steps {
                echo 'testing the application here'
            }
        }
        stage('deploy') {
            steps {
                echo "deploying the application here"
            }
        }
    }
}