#!groovy
pipeline {
	agent {
		docker {image 'maven:3.5.0'}
	}
	stages {
		stage('Maven install') {
			agent {
				docker {
					steps {
						sh 'mvn clean install'
				}
			}
		}
	}
}
