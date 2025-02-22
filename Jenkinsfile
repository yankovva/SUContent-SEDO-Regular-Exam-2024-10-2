pipeline{
    agent any
    stages {
        stage('Build project'){
            steps{
                sh 'dotnet build'
            }
        }
        stage('Run tests'){
            steps{
                sh 'dotnet test'
            }
        }
    }
}
