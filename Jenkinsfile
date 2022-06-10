pipeline {
    agent any
	
    stages {
	stage ('Compile Stage') {
            stpes {
	    	withMaven(maven : 'maven-3.8.1') {
	            sh 'mvn clean compile'
	        }
	    }
    	}
	stage ('Testing Stage') {
            stpes {
	    	withMaven(maven : 'maven-3.8.1') {
	            sh 'mvn clean test'
	        }
	    }
    	}
    }
}
