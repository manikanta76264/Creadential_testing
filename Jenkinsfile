pipeline{
	agent any
	stages{
		stage("testing credential"){
			steps{
				withCredentials([usernamePassword(credentialsId: 'credentials_testing', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')])
				echo %USERNAME%
					}
		}
	}
}
