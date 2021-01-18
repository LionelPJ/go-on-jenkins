pipeline {
	agent any

	tools {
		go 'Go 1.15.6'
	}
	
	environment {
		GO111MODULES = 'on'
	}
	
	stages {
		stage('Build') {
			steps {
				sh 'go build'
			}
		}
	}
}	
