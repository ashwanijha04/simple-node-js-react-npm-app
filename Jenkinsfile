pipeline {
    agent any
    stages {
        stage('Pre-Build') { 
            steps {
                sh 'npm install' 
            }
        }

        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
    }
}
