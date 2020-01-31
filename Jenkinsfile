pipeline{
	agent any
	stages{
		stage("testing global creadentials"){
			steps{
		              withCredentials([usernamePassword(credentialsId: 'credentials_testing', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')])
				echo "%USERNAME%  %PASSWORD%"
				}
			}

		}
	
}
