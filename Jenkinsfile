pipeline {
	agent none
	stages {
		stage('test') {
			agent 'linux'
			steps {
				sh 'echo hello_WORLD'
			}
		}
		stage('win') {
			agent 'windows'
			steps {
				bat 'echo HELLO_WORLD'
			}
		}
	}
}
