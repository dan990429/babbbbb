pipeline {
	agent none
	stages {
		stage('test') {
			agent {
				label 'linux'
			}
			steps {
				sh 'echo hello_WORLD'
			}
		}
		stage('win') {
			agent { 
				label 'windows'
			}
			steps {
				bat 'echo HELLO_WORLD'
			}
		}
	}
}
