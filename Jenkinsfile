pipeline {
    agent any

    stages {
        stage('Fecha') {
            steps {
                sh 'date'
            }
        }
        stage('Usuario') {
            steps {
                sh 'wc -l /etc/passwd'
            }
        }
    }
}
