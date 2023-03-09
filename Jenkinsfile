#!groovy
pipeline {
	agent any
	stages {
		stage('Maven install') {
			steps {
				sh 'mvn clean install'
			}
		}
	}
}
