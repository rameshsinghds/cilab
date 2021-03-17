pipeline {
    agent any
    stages {
        stage('compile') {
            steps {
                sh "mvn combile"
            }
        }
        stage('Unit Test') {
            steps {
                sh "mvn test"
            }
        }
    }
}
