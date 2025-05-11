
pipeline {
    agent any

    parameters {
        booleanParam(name: 'SKIP_TEST', defaultValue: false, description: 'Skip the Test stage')
    }

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
    }
}