#!groovy
pipeline {
	agent none
	stages {
		stage('Maven install') {
			steps {
				sh 'mvn clean install'
			}
		}
	}
}
