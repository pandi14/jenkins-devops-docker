#node {
#	stage('Build') {
#		echo "Build"
#	}
#	stage('Test') {
#		echo "Test"
#	}
#}

pipelin{
	agent{ docker { image 'maven:3.6.3'} }
	stages{
		stage ('Build'){
			steps{
			sh 'mv --version'
			echo "Build"
			}
		}
	      }
	     }
