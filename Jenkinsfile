pipeline {
agent{docker{image 'maven:3.6.3'}}
	stages{
stage('Build'){
	steps{
		sh 'mvn --vesrion'
		}
	}
	stage('Test') {
	steps{
		echo "Test"
		}
	}
	stage('Integration Test') {
	steps{
		echo "Integration Test"
		}
	}
}
}