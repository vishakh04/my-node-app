pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repo...'
            }
        }

        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Run App') {
            steps {
                bat 'npm start'
            }
        }

        stage('Test') {
            steps {
                echo 'No tests defined yet.'
            }
        }
    }
}
