pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repo...'
                // Git is already handled by default in Declarative Pipeline
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run App') {
            steps {
                bat 'start /b npm start'
            }
        }


        stage('Test') {
            steps {
                echo 'No tests defined yet.'
            }
        }
    }
}
