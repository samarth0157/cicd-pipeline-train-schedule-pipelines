pipeline{

 agent any
 stages {
     stage ('build') {
        
         steps {
             echo 'running build automation'
             sh './gradlew build -- no-deamon'
             archiveArtifacts artifact:'dist/trainSchedule.zip'           
           
         }
       
     }
 
 }
}
