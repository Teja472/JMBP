pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact for project samplewebapp"
			   """
               
           }
       }
       stage('Reading branch wise')
       {
       when
       {
       branch "feature*"
       }
       steps
       {
       echo " It is only for Feature branch"
       }
       }

       stage('Deploy Code') {
	   
<<<<<<< HEAD
	  steps {
=======
          steps {
>>>>>>> 792747e44808f9c3532432ae94c47c6784d9b2e4
               sh """
               echo "Deploying Code"
			   """
               
          }
      }
      }
      }

