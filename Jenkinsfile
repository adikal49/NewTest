pipeline {
	agent any
	triggers {
		cron(' * * * * * ')
	}
	stages {
		stage ('validate') {
			steps {
				echo "Validating"
				//sh 'mvn --version'
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
