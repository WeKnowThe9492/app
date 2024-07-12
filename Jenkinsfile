pipeline {

agent {
		label {
		
				label 'built-in'
				customWorkspace '/data/pipeline'
				
		}

}

stages {
			stage ('create-file-1'){
			
			steps {
						sh "rm -rf *"
						sh "touch file1"
			}
			
			}
}
}
