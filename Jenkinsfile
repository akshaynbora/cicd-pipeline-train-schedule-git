pipeline {

  agent any 
   stages {
    stage ('Build')
     {
       steps {
         echo "Running the build automation"
         
         archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
   }
}
