// Powered by Infostretch 

timestamps {

node () {

	stage ('free_style_sample - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '2c9d93af-6ff4-43d5-87a9-5a618aed1ce0', url: 'https://github.com/ravikiranbukka/PurdueCodes']]]) 
	}
	stage ('free_style_sample - Build') {
 			// Shell build step
sh """ 
echo "Hello" 
 """ 
	}
}
}