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
    }
}