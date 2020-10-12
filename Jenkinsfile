pipeline {
    agent { docker { image 'python:alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
		sh 'python3 pipeline.py'
            }
        }
    }
}

