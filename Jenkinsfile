pipeline {
    agent any
    stages {
        stage('Build') {
            steps{
                bat 'mvn clean'
            }
        }
        stage('Test') {
            steps{
                bat 'mvn Test'
            }
        }
        stage('Deploy') {
            steps{
                bat 'mvn package'
            }
        }
    }
    
}
