// Powered by Infostretch 

timestamps {

node () {

	stage ('Case_study_saran - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '', url: 'https://github.com/kajasaran/2020_03_DO_Boston_casestudy_part_1.git']]]) 
	}
	stage ('Case_study_saran - Build') {
 			// Shell build step
sh """ 
python web.py 
 """ 
	}
}
}
