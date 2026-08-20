pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'python Subtraction.java'
            }
        }

        stage('Run') {
            steps {
                sh 'python Subtraction'
            }
        }
    }
}
