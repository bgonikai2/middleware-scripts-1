pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello '
                sleep 9
            }
        }
        stage('Build') {
            steps {
                echo 'Build'
                sleep 7
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
                sleep 5
            }
        }
        stage('Docker') {
            steps {
                echo 'Docker'
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
