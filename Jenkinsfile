pipeline {
    agent { docker { image 'python:3.13.2-alpine3.21' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Welcome to Jenkins!"'
                sh '''
                    echo "Multiline shell steps works too! Cool right?"
                    ls -lah
                '''
                sh 'python --version'
            }
        }
    }
}