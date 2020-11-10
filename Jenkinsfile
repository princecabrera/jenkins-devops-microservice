// SCRIPTTED PIPELINES WHERE STAGE BLOCKS ARE OPTIONAL

// DECLARATIVE
pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
	}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps { 
				echo "TESTED!"
			}
		}	
	} 
	
	post {
		always {
			echo 'Im awesome, I run always'
		}
		success {
			echo 'I run when you are successful'
		}
		failure {
			echo 'I run when you fail'
		}
	}
}
