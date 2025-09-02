pipeline {
	agent any
	stages {
		stage ("Build") {
			steps{
				echo "Build"
			}
		}
		stage ("Test") {
			steps{
				echo "Test"
			}
		}
		stage ("Integration Test") {
			steps{
				echo "Integration Test"
			}
		}
	} post {
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
