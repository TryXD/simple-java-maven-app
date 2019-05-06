pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
        stage('who am i') {
            steps {
                sh 'whoami'
            }
        }
        stage('mvn -v') {
            steps {
                sh 'mvn -v'
            }
        }
        stage('docker -v') {
            steps {
                sh 'docker -v'
            }
        }
    }
}
