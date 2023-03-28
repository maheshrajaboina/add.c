pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'gcc add.c -o add'
            }
        }
        stage('Test') {
            steps {
                sh './add'
            }
        }
    }
}
