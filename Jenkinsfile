// Declarative pipeline
pipeline {

    agent any
    stages {
        stage('Compile stage') {
            steps {
                sh "mvn clean compile" 
            }
        }
        stage('Compile stage') {
            steps {
                sh "mvn test" 
            }
        }
    }
} 
