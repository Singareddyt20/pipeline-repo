pipeline {
    agent any

    stages {
	    stage ('compile stage') {
        	stpes {
	    	    withMaven(maven : 'maven-3.8.1') {
	        	sh 'mvn clean compile'
	            }
		}
    	}
    }
}
