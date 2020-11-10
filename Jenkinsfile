// SCRIPTTED PIPELINES WHERE STAGE BLOCKS ARE OPTIONAL

// DECLARATIVE
node {
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
}
