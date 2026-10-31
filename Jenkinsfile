pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checkout successful'
            }
        }

        stage('Build') {
            steps {
                sh 'chmod +x app.sh'
                sh './app.sh'
            }
        }
    }
}
