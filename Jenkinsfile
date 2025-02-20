pipeline{
    agent any
    stages{
        stage('NPM Install'){
            steps{
                bat 'npm install'
            }
        }
        stage('Run intergartion test'){
            steps{
                bat 'npm run test'
            }
        }
        stage('Deploy to STAGINH'){
            steps{
                echo 'Deploying to staging'
            }
        }
        stage('Deploy to PRODUCTION'){
            steps{
                echo 'Deploying to production'
            }
        }
    }
}