pipeline {
    agent any

    stages {
        stage('Check') {
            steps {
                sh 'node --check Multiplication.js'
            }
        }

        stage('Run') {
            steps {
                sh 'node Multiplication.js'
            }
        }
    }
}
