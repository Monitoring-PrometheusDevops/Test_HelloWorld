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
   stage('Test'){
    steps{
     echo "testing success"
     sh """
         ruby hello.rb
      """
    }
   }
 	 }
  }
 
