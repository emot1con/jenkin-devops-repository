pipeline {
	agent any
	stages {
		stage ("Build") {
			steps{
				echo "Build"
			}
		}
		stage ("Build Test") {
			steps{
				echo "Build Test"
			}
		}
		stage ("Staging Test") {
			steps{
				echo "Staging Test"
			}
		}
		stage ("Integration Test") {
			steps{
				echo "Integration Test"
			}
		}
	} 
	
	post {
		always {
			echo "Cleaning up..."
		}
		success {
			echo "This build was successful!"
		}
		failure {
			echo "This build failed."
		}
	}
}
