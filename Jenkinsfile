pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'javac HelloWorld.java'
                sh 'java HelloWorld'
            }
        }
    }
}
