pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello '
                sleep 5
            }
        }
        stage('Build') {
            steps {
                echo 'build'
                sleep 5
            }
        }
        stage('Test') {
            steps {
                echo 'test'
                sleep 5
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploy'
                sleep 7
            }
        }
    }
}
