pipeline {
  agent any
 stage  {
  stage ('Build') {
   steps {
    echo 'Running Build automation for Ora demo'
    sh './gradlew build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
   }
  }
   
 }
 
}
 
