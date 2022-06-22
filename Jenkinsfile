peline{
	environment{
        GIT_URL = 'git@github.com/ShanmPrasadK/myjpetstore.git' 
        GIT_CREDS_ID = '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' 
        GIT_BRANCH = '*/master'

		}
	stages{
		stage("Checkout Code"){
			steps{
				script{
				checkout([$class: 'GitSCM', branches: [[name: GIT_BRANCH]], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], 
						userRemoteConfigs: [[credentialsId:GIT_CREDS_ID , url: GIT_URL]]])
				}
			}
		}
}
}
