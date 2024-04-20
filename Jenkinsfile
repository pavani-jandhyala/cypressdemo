pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building application"
            }
        }
        stage('Test'){
            steps {
                // sh 'make check'
                // junit 'reports/**/*.xml'
                bat "npm i"
                bat "npx cypress run"
            }
        }
        stage('Deploy') {
            steps {
                sh "Building application"
            }
        }
    }
}
