pipeline {
   agent any
  // tools {
    //  maven 'Maven'
   //}
   stages {
       stage("Conditional Multibranch Build branch surf") {
           steps {
               echo "Conditional Multibranch Build branch jpmc" 
               sleep 5
           }
       }
       
       stage("Conditional Multibranch Test branch surf") {
          when {
            branch 'scratch/surf'
          }
          steps {
               echo "Conditional Multibranch Build branch jpmc" 
               sleep 5
           }           
        } 
        stage("Conditional Multibranch Deploy branch surf") {
           steps {
             snDevOpsChange()
               echo "Conditional Multibranch Deploy branch jpmc" 
               sleep 5
           }
        }
      }
  }
