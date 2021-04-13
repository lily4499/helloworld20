pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sleep 4
            }
        }
        stage('build') {
            steps {
                echo 'Hello build'
                sh 'pwd'
            }
        }
        stage('test') {
            steps {
                echo 'Hello test'
                sh 'docker ps'
            }
        }
    }
}
