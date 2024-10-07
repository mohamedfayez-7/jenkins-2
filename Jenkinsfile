pipeline {
    agent any

    parameters {
        string(name: 'ENVIRONMENT', defaultValue: 'dev', description: 'Environment to deploy to')
    }

    stages {
        stage('Print Environment') {
            steps {
                echo "Deploying to ${params.ENVIRONMENT}"
            }
        }
    }
}
