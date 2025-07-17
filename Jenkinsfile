pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                echo 'Running Stage 1...'
                // Simulate work (e.g., checkout, setup)
                sh 'echo Hello from Stage 1'
            }
        }

        stage('Stage 2') {
            steps {
                echo 'Running Stage 2...'
                // Simulate work (e.g., build)
                sh 'echo Hello from Stage 3'
            }
        }

        stage('Stage 3') {
            steps {
                echo 'Running Stage 3...'
                // Simulate work (e.g., test or deploy)
                sh 'echo Hello from Stage 3'
            }
        }
    }

    post {
        always {
            echo 'Pipeline completed.'
        }
    }
}
