pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           echo "THIS IS NEW FEATURE BRANCH" 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application...By JENKINS"'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }
	

     }
  
   	}

   }
