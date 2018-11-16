// Powered by Infostretch 

timestamps {

node ('raptor-builder') { 

	stage ('freestylejob - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '2c9d93af-6ff4-43d5-87a9-5a618aed1ce0', url: 'https://github.com/ravikiranbukka/PurdueCodes.git']]]) 
	}
	stage ('freestylejob - Build') {
 	
withEnv(["JAVA_HOME=${ tool '"+JDK+"' }", "PATH=${env.JAVA_HOME}/bin"]) { 
		// Shell build step
sh """ 
echo "Testing the convert to pipeline plugin." 
 """ 
	}
}
}
}