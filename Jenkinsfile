pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/NaeemKK/delete.git'
            }
        }
        stage('Build') {
            steps {
                sh 'gcc -o hello hello.c'
            }
        }
        stage('Run') {
            steps {
                sh './hello'
            }
        }
    }
}

