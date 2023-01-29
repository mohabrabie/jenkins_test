pipeline {
    agent any

    stages {
        stage('Build') {
            // build
            steps {
                // run and build the image
                sh """
                    echo "build and run the image here";
                    ls;
                """
            }
        }
        stage('test') {
            steps {
                sh """
                    echo 'testing the application here'
                    """
            }
        }
        stage('deploy') {
            steps {
                sh """
                    echo "deploying the application here"
                    """
            }
        }
    }
}