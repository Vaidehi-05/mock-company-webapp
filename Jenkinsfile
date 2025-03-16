pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh './gradlew assemble'  // Build stage
            }
        }
        stage('Test') {
            steps {
                sh './gradlew test'  // Test stage
            }
        }
    }
}
