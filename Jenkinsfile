pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'python3 -m py_compile Addition.py'
            }
        }

        stage('Run') {
            steps {
                sh 'python3 Addition.py'
            }
        }
    }
}
