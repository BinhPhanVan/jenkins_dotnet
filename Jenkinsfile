pipeline {
    agent any
    stages {
        stage('Build Stage') {
            steps {
                sh 'cd Demo.API'
                sh 'dotnet build'
                sh 'ls'
                sh 'cd ../'
            }
        }
        stage('Test Stage') {
            steps {
                sh 'docker-compose up -d'
            }
        }
        stage("Release Stage") {
            steps {
                sh 'echo "hello"'
            }
        }
        stage('Deploy Stage') {
            steps {
                sh 'echo "hello"'
            }
        }
    }
}