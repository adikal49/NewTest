pipeline {
	agent {
		docker {
			image 'maven:3.6.3'
		}
	}
	stages {
		stage ('validate') {
			steps {
				echo "Validating"
				sh 'mvn --version'
			}
		}
		stage ('compile') {
			steps {
				echo "Compiling"
			}
		}
		stage ('test') {
			steps {
				echo "Testing"
			}
		}
		stage ('package') {
			steps {
				echo "Package"
			}
		}
		stage ('verify') {
			steps {
				echo "Verifying"
			}
		}
		stage ('install') {
			steps {
				echo "Installing"
			}
		}
		stage ('deploy') {
			steps {
				echo "Deploying"
			}
		}
	}
}
