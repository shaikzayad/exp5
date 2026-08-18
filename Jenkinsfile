pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh ' Subraction.py'
            }
        }

        stage('Run') {
            steps {
                sh ' Subtraction'
            }
        }
    }
}
