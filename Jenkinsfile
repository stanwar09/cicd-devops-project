pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                echo 'Cloning from GitHub...'
            }
        }

        stage('Build') {
            steps {
                echo 'Running python app'
                bat 'python app.py'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Docker stage later'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage'
            }
        }
    }
}
S