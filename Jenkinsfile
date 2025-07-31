pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac Difference.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Difference'
            }
        }
    }

    post {
        always {
            echo 'Pipeline for Difference.java completed.'
        }
    }
}
