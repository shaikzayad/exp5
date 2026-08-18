pipeline {
    agent any

    stages {
        stage('Check') {
            steps {
                sh 'node --check multiplication.js'
            }
        }

        stage('Run') {
            steps {
                sh 'node multiplication.js'
            }
        }
    }
}
