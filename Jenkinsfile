pipeline {	 
 	agent any
 	stages {
 	stage('Checkout scm') { 
 	steps {
 	checkout scm
 	  }
 	}
 	stage('Build & Run') { 
 	steps {
 	  sh """
        ruby hello.rb
    """
    
 	  }
 	 }
  }
 }
