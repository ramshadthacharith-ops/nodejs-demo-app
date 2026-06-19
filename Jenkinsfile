pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git credentialsId: 'git-creds',
                url: 'https://github.com/YOUR-USERNAME/YOUR-REPO.git'
            }
        }

        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
    }
}
