pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Compiler le fichier Java
                bat 'javac HelloWorld.java'

                // Exécuter le fichier Java
                bat 'java HelloWorld'
            }
        }
    }
}
