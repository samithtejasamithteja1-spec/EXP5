pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac Addition'
            }
        }

        stage('Run') {
            steps {
                sh 'Addition'
            }
        }
    }
}
