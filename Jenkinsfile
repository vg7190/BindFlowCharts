pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                echo 'Build!'
                sh "cc hello.c"
            }
        }
        stage('Test'){
            steps {
                echo 'Test!'
                sh "./a.out"
            }
        }
        stage('Deploy'){
            steps {
                echo 'Deploy!'
            }
        }
    }
}
