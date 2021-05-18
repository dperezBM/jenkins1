pipeline {
    agent any
    environment {
        FICHERO = "/etc/passwd"
    }
    stages {
        stage('Fecha') {
            steps {
                sh 'date'
            }
        }
        stage('Usuario') {
            steps {
                sh 'wc -l {FICHERO}'
            }
        }
    }
}
