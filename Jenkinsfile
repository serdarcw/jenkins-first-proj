pipeline {
    agent { docker { image 'python:alpine' } }
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
		sh 'apt install git'
		sh 'apt install python3'
		sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
