pipeline{
	agent any
	stages{
		stage('check-out'){
			steps{
				git  'https://github.com/jai-demo/pipeline-demo' 
			}
		}
		
		stage('Job1'){
			steps{
				bat 'Job1.bat'
			}
			
		}
		
		stage('Job2'){
			steps{
				bat 'Job2.bat'
			}
		}
		
		stage('Job3'){
			steps{
				bat 'Job3.bat'
			}
		}
	}
}
