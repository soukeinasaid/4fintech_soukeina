
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Alaa-Rami/DevOps-AppGestionDesProjets.git'
            }
        }

        stage('Verification') {
            steps {
                echo 'Repository cloned successfully!'
                sh 'ls -la'
            }
        }
    }
}





















