pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
				// Invoke command to build with maven
                bat 'mvn clean install'
            }
        }
    }
}