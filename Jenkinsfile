pipeline {
  agent any
  stages {
   stage ('build'){
     Steps {
       echo 'Running build automation'
       sh'./gradlew build --no-damon'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
   }
  }
}
