pipeline {
   agent{
	   label 'nodejs'
	 }
	 tools {
				nodejs "Node 8.4.0"
				}
   stages {
	    stage ('build') {
				 steps {
				    sh 'npm install'
				 }
			}
	 }
}
