pipeline {
  agent any
  stages {
   stage ('build'){
     steps {
       echo 'Running build automation'
       sh'./gradlew build --no-damon'
       archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
   }
  }
}
