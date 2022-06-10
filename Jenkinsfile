pipeline {
    agent any

    stages {
        stpes {
	    withMaven(maven : 'maven-3.8.1') {
	        sh 'mvn clean compile'
	    }
	}
    }
}
