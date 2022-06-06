pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Clarusway_Way to Reinvent Yourself****"
                sh 'echo using shell within Jenkinsfile***'
                echo 'not using shell in the Jenkinsfile***'
            }
        }
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself***'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
        stage('test') {
            steps {
                echo 'Test - Clarusway_Way to Reinvent Yourself - Test'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}