node{
  stage('SCM Checkout'){
	
		git 'https://github.com/akmishra07/jenkinsproject.git'
	}
  Stage('Compile-Package'){
	   def mvnHome =  tool name: 'Maven', type: 'maven'
	  sh "${mvnHome}/bin/mvn package"
        }
        }
