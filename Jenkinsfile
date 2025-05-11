
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }

        stage('Upload Test Results') {
            steps {
                echo 'Uploading test results...'
                junit 'results.xml'
                rchiveArtifacts artifacts: 'results.xml', fingerprint: true
            }
        }
    }
}