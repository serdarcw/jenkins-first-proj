pipeline {
    agent { docker { image 'python:alpine' } }
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'apt install git'
		sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
