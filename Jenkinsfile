pipeline{
	agent any
	stages{
		stage('check-out'){
			steps{
				git branch: 'main', url: 'https://github.com/jai-demo/pipeline-demo'  /* repository is  public */ 
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
