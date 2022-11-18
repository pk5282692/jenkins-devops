pipeline {
   agent any
   stages {
	stage('build') {
	   steps {
		echo "Build"
	   }
        }
   	stage('test') {
     	   steps {	 
	  	 echo "Test"
	   }
  	}
        stage('integration test') {
	   steps {
		echo "Integration Test"
	   }
   	}
   }
   post {
	   always {
		   echo 'iam awesome i run always'
	   }
	   success {
		   echo 'i run when you are success'
	   }
	   failure {
		   echo 'i run when you fail'
	   }
   }
	
}
