// Powered by Infostretch 

timestamps {

node ('raptor-builder') { 

	stage ('free_plus_one - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/test']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '2c9d93af-6ff4-43d5-87a9-5a618aed1ce0', url: 'https://github.com/ravikiranbukka/PurdueCodes']]]) 
	}
	stage ('free_plus_one - Build') {
 			// Shell build step
sh """ 
echo "Hello_plus_one" 
 """ 
	}
}
}