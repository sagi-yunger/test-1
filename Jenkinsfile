pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('test') {
            steps {
                sh 'PYTHONPATH=. pytest'
            }
        }
    }
}
