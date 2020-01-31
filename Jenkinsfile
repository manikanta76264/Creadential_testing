pipeline{
	agent any
	stages{
		stage("testing credential"){
			withCredentials([usernamePassword(credentialsId: 'credentials_testing', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')])
			steps{
			 echo %USERNAME%
				}
		}
	}
}
