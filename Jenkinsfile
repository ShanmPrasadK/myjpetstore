pipeline{
	agent any
	environment{
        GIT_URL = 'git@github.com:ShanmPrasadK/myjpetstore.git' 
        GIT_CREDS_ID = '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' 
        

		}
	stages{
		stage("Checkout Code"){
			steps{
				git 'GIT_URL'
			}
		}
}
}
