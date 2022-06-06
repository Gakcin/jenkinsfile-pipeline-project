pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Clarusway_Way to Reinvent Yourselfxxx"
                sh 'echo using shell within Jenkinsfilexx'
                echo 'not using shell in the Jenkinsfilexx'
            }
        }
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}