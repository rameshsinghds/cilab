pipeline {
    agent any
    stages {
        stage('compile') {
            steps {
                sh "mvn compile"
            }
        }
        stage('Unit Test') {
            steps {
                sh "mvn test"
            }
        }
    }
}
