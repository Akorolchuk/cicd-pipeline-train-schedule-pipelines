pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
         echo 'Runing build automation'
         sh './gradlew build --no-daemon'
         archiveArtifcats artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
