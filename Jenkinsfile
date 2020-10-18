pipeline {
   agent any
   tools {
      maven 'Maven'
   }
   stages {
       stage("Conditional Multibranch Build") {
           steps {
               echo "Conditional Multibranch Build" 
               sleep 5
           }
       }
       
       stage("Conditional Multibranch Test") {
          steps {
               echo "Conditional Multibranch Build" 
               sleep 5
           }           
        } 
        stage("Conditional Multibranch Deploy") {
           steps {
             // snDevOpsChange()
               echo "Conditional Multibranch Deploy" 
               sleep 5
           }
        }
      }
  }
