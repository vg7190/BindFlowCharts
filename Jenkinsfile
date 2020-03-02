pipeline {
    agent any
    stages {
        stage('script stage check'){
            steps{
                script{
                    echo "PATH is anoop"
                }
            }
        }
        stage('Build'){
            steps {
                echo 'Build!'
                sh "cc hello.c"
            }
        }
        stage('Test'){
            steps {
                echo 'Test!'
                sh "./a.out $name"
            }
        }
        stage('Deploy'){
            steps {
                echo 'Deploy!'
            }
        }
    }
}
