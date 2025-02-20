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
        stage('Approval for Production Deployment'){
            steps{
                script{
                    input message: 'Proceed with production deployment?', ok: 'Deploy'
                }
            }
        }
        stage('Deploy to PRODUCTION'){
            steps{
                echo 'Deploying to production'
            }
        }
    }
}