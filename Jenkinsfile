
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add deployment commands here
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded!'

            // You can add further actions here, such as sending notifications or triggering other jobs
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
