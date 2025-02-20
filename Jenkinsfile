pipeline{
    agent any
    stages{
        stage('NPM Install'){
            steps{
                bat 'nom install'
            }
        }
        stage('Run intergartion test'){
            steps{
                bat 'npm run test'
            }
        }
    }
}