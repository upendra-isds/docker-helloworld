pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker build -f ./dockerfile'
            }
        }
    }
}
