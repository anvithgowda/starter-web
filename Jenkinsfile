pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                sh 'java -version'
            }
        }
        stage('Test'){
            steps {
                sh 'git --version'
            }
        }
        stage('Deploy') {
            steps {
                sh 'jenkins --version'
            }
        }
    }
}
