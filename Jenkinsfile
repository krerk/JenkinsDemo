pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }

        stage('run') {
            steps {
                sh 'echo "Running"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Sample"'
            }
        }   
    }
}
