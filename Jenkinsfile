pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo "build"
            }
        }
        stage('Test'){
            steps {
                sh 'bash test.sh'
            }
        }
        stage('Deploy') {
            steps {
                echo "deployed"
            }
        }
    }
}