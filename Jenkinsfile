// Declarative pipeline
pipeline {
    agent any
	stages {
	    stage ('Compile Stage'){
		   steps {
		       withmaven(maven : 'maven-3.6.0') {
			       sh 'mvn clean compile'
			    }
		    }
	    }
     }
}  
