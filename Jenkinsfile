pipeline{
  agent any{
    stages{
      stage('Build'){
        steps{
          echo 'runnung build automation'
          sh './gradlew build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
         }
       }
    }
  }
}
