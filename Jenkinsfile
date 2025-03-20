pipeline {
    agent { docker { image 'gradle:7.5.1-eclipse-temurin-17-alpine' } }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                sh 'echo Test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'Deploying..'
            }
        }
    }
}
