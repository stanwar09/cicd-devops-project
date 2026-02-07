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
                sh 'python3 app.py'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Docker stage soon'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage soon'
            }
        }
    }
}
