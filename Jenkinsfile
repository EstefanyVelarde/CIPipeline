pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
            }
        }
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}