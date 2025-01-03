pipeline {
    agent any  // Exécute la pipeline sur n'importe quel agent disponible

    stages {
        // Étape 1 : Build HelloWorld
        stage('Build HelloWorld') {
            steps {
                echo 'Building HelloWorld...'
                sh 'javac HelloWorld.java'
            }
        }

        // Étape 2 : Run HelloWorld
        stage('Run HelloWorld') {
            steps {
                echo 'Running HelloWorld...'
                sh 'java HelloWorld'
            }
        }

        // Étape 3 : Build Merci
        stage('Build Merci') {
            steps {
                echo 'Building Merci...'
                sh 'javac Merci.java'
            }
        }

        // Étape 4 : Run Merci
        stage('Run Merci') {
            steps {
                echo 'Running Merci...'
                sh 'java Merci'
            }
        }

        // Étape 5 : Build DeRien
        stage('Build DeRien') {
            steps {
                echo 'Building DeRien...'
                sh 'javac DeRien.java'
            }
        }

        // Étape 6 : Run DeRien
        stage('Run DeRien') {
            steps {
                echo 'Running DeRien...'
                sh 'java DeRien'
            }
        }
    }
}
