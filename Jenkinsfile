// Declarative pipeline
pipeline {
    agent any
	stages {
	    stage ('Compile Stage'){
		   steps {
		       withMaven(maven : 'maven-3.6.0') {
			       sh 'mvn --version'
			    }
		    }
	    }
     }
}  
