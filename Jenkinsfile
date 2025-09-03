pipeline{
	agent any
	// agent { docker { image 'maven:3.6.3' } }	
	stages{
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
		stage ("Prod Test"){
			steps{
				echo "Prod Test"
			}
		}
	}
	post {
		always{
			echo "Cleaning Up..."
		}
		success{
			echo "This build was successfully completed"
		}
		failure{
			echo "This build has failed"
		}
	}
}