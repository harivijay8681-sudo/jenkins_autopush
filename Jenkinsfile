pipeline {
    agent any

    parameters {
        string(name: 'ENV', defaultValue: 'dev', description: 'Environment')
    }

    stages {

        stage('Build') {
            steps {
                echo "Building in ${params.ENV} environment..."
            }
        }

        stage('Test') {
            steps {
                echo "Testing in ${params.ENV} environment..."
            }
        }
    }
}
