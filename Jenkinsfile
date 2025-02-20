pipeline {
    agent any // Specifies that the pipeline can run on any available agent

    stages {
        stage('NPM Install') {
            steps {
                bat 'npm install' // Use bat for Windows agents
            }
        }
        stage('Run Integration Test') { // Corrected spelling of "Integration"
            steps {
                bat 'npm run test' // Use bat for Windows agents
            }
        }
        stage('Deploy to STAGING') { // Corrected spelling of "STAGING"
            steps {
                echo 'Deploying to staging'
            }
        }
        stage('Deploy to PRODUCTION') { // Corrected spelling of "PRODUCTION"
            steps {
                echo 'Deploying to production'
            }
        }
    }
}
