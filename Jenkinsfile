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
                sh 'npm i'
                sh 'npx cypress run'
            }
        }
        stage('Deploy') {
            steps {
                sh "Building application"
            }
        }
    }
}
