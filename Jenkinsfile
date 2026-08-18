pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'python3 -m py_compile Subtraction.py'
            }
        }

        stage('Run') {
            steps {
                sh 'python3 Subtraction.py'
            }
        }
    }
}
