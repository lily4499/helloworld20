pipeline {
    agent any
    tools {
        Maven 'M2_HOME'
    }

    stages {
        stage('build') {
            steps {
                sh 'mvn clean'
                sh 'mvn install'
                sh 'mvn package'
            }
        }
        stage('check') {
            steps {
                echo 'Hello check'
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
