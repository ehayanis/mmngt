pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker build -t mmngt:0.5 .'
            }
        }

        stage('Deploy') {
            steps {
                sh 'docker push mmngt:0.5'
            }
        }
    }
}