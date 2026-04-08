pipeline {
    agent any

    parameters {
        string(name: 'ENV', defaultValue: 'dev', description: 'Environment')
    }

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/harivijay8681-sudo/jenkins_autopush.git'
            }
        }

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
