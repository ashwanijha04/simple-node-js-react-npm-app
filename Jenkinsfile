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

        stage('Post-Build') {
            steps {
                sh 'npm run build'
            }
        }
    }
}
