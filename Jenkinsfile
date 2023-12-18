pipeline {
    agent {
        label 'ansible'
    }

    stages {
        stage('first') {
            steps {
                sh 'molecule test'
            }
        }
    }
}