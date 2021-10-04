//SCRIPTED

//DECLARATIVE
pipeline {
	agent any
	stages{
		stage('Build'){
			steps{
				echo "Build"
			}
		}
		stage('Test'){
			steps{
				echo "Test"
		
			}
		}
		stage('integration Test'){
			steps{
				echo "integration Test"
				
			}
		}
	} post{
		always{
			echo 'i run always'
		}
		success {
			echo 'i run success'
		}
		failure{
			echo 'i run failure'
		}
		

	}
	
		
	
}
