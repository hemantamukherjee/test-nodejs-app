pipeline { 
  
   agent any

   stages {
   
     stage(' Dependencies') { 
        steps { 
           sh 'echo "testing application..."'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}
   
   post{
      success {
           sh 'echo "i will always get executed"'
      }
     always {
           sh 'echo "i will always get executed"'
      }
     
   }
   }
