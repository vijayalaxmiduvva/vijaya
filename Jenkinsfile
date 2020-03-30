// Declarative pipeline
pipeline {
    agent any
    tools {
        maven 'Maven_3.6.0' 	
    stages {
        stage('Compile stage') {
            steps {
                bat "mvn clean compile"
	        }
        }
    }
  }	
}
