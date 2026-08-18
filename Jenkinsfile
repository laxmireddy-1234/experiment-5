pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'python -m py_compile Addition.py'
            }
        }

        stage('Run') {
            steps {
                sh 'python Addition.py'
            }
        }
    }
}
