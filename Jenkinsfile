pipeline{
	agent any
	
		stages{
			withCredentials([usernamePassword(credentialsId: 'credentials_testing', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')])
			stage("testing global creadentials"){
				steps{
				echo "${USERNAME}  ${PASSWORD}"
				}
			}

		}
	
}
