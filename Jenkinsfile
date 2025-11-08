pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Example: run a build command
                sh 'echo "Build completed successfully!"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example test simulation
                sh 'echo "All tests passed!"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Example deployment simulation
                sh 'echo "Deployment done!"'
            }
        }
    }

    post {
        success {
            echo '✅ Build and deployment successful!'
        }
        failure {
            echo '❌ Build failed. Check logs for errors.'
        }
    }
}
