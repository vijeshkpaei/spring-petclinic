#!groovy
pipeline {
	agent none
	stages {
		stage('Maven install') {
			agent {
				docker {
					image 'maven:3.8.0'
				}
			}
			steps {
				sh 'mvn clean install'
			}
		}
	}
}
