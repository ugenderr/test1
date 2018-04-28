pipeline {
   agent { label "nodejs"}
	 tools {nodejs "Node 8.4.0"}
   stages {
	    stage ("Build") {
				 steps {
				    sh "npm install"
				 }
			}
	 }
}
