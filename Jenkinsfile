pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello '
                sleep 9
            }
        }
        stage('Docker') {
            steps {
                echo 'Docker'
                sleep 7
            }
        }
        stage('Build') {
            steps {
                echo 'Build'
                sleep 5
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
                sleep 10
            }   
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
                sleep 8
            }
        }    
    }
}
