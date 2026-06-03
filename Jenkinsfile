pipeline {
    agent any
    
    tools {
        maven 'Maven'
    }

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/Rupesh079/maven.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
