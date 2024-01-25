pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add deployment steps here
            }
        }
    }
    
    post {
        success {
            echo 'Pipeline executed successfully!'
            // Add post-success actions here
        }
        failure {
            echo 'Pipeline failed!'
            // Add post-failure actions here
        }
    }
}

