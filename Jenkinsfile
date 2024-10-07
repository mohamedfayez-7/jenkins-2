pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/mohamedfayez-7/jenkins-2.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
            }
        }
    }
}
