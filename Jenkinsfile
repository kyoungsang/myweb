pipeline {
    agent { docker { image 'gradle:7.5.1-eclipse-temurin-17-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                sh "echo 'Test'"
            }
        }
    }
}
