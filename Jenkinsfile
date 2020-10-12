pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
		sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}
