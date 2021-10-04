//SCRIPTED

//DECLARATIVE
pipeline {
	//agent any
    agent { docker { image 'maven:3.6.3'} }
	stages{
		stage('Build'){
			steps{
				sh 'mvn --version'
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
	} 
	post{
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
