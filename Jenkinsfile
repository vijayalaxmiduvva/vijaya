// Declarative pipeline
pipeline {
    agent any

    stages {
        stage('Compile Stage') {
            steps {
                sh "mvn compile"
            }
        }
        stage('Package') {
            steps {
                sh "mvn package"
            }
        }
        stage('Deploy') {
            steps {
                sh "mvn deploy"
            }
        }
   }
}
