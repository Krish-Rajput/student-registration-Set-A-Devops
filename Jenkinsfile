pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Krish-Rajput/student-registration-Set-A-Devops.git'
            }
        }
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}