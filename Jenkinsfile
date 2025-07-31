pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                sh 'javac Difference.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Difference'
            }
        }
    }

    post {
        always {
            echo 'Pipeline for Difference.java completed.'
        }
    }
}
