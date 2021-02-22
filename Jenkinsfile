pipeline {
   agent any
  // tools {
    //  maven 'Maven'
   //}
   stages {
       stage("Conditional Multibranch Build branch jpmc") {
           steps {
               echo "Conditional Multibranch Build branch jpmc" 
               sleep 5
           }
       }
       
       stage("Conditional Multibranch Test branch jpmc") {
          when {
            branch 'scratch/jpmc'
          }
          steps {
               echo "Conditional Multibranch Build branch jpmc" 
               sleep 5
           }           
        } 
        stage("Conditional Multibranch Deploy branch jpmc") {
           steps {
             //snDevOpsChange(ignoreErrors:true)
               echo "Conditional Multibranch Deploy branch jpmc" 
               sleep 5
           }
        }
      }
  }
