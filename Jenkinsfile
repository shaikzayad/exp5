pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'python3 -m py_compile Subraction.py'
            }
        }

        stage('Run') {
            steps {
                sh 'python3 Subraction.py'
            }
        }
    }
}
